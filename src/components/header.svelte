<svelte:head>
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
</svelte:head>

<script>
	import '../app.css';
    import {onMount} from 'svelte';

    // @ts-ignore
    let board;
    // @ts-ignore
    let open;
    // @ts-ignore
    let close;
    onMount(() =>{
        // @ts-ignore
        open.addEventListener('click',() =>{
            // @ts-ignore
            board.style.display = 'block';
        });
        // @ts-ignore
        close.addEventListener('click',() =>{
            // @ts-ignore
            board.style.display = 'none';
        });
    })
</script>

<style scoped>
    ul>li>a:hover{
        width:fit-content;
        height:100%;
        padding-bottom:16px;
        background-color: transparent;
        border-bottom: 1px solid orange;
        transition: 1s ease-in-out;
    }
    #btn1:hover{
        border:1px solid orange;
        transition: 1s ease-in-out;
    }
    #cnw{
        font-family: 'Poppins', sans-serif;
    }
    #tranmenu{
        transition:2s esae-in-out;
        animation:1s ease-in-out fadey;
    }

    @keyframes fadey{
        from{
            opacity:0.5;
        }
        to{
            opacity:1;
        }
    }
</style>

<header class="w-full bg-black flex justify-between p-4 items-center fixed top-0 z-[99]">
    <div class="flex ml-[30px] md:text-xl md:font-bold text-white font-['Poppins', sans-serif]">
        <span class="text-yellow-600">
            <i class="las la-kiwi-bird"></i>
        </span>
        <a href="/">NftsHot</a>
    </div>
    <!---->
    <div class="hidden md:flex">
        <ul class="flex md:hidden lg:flex lg:space-x-14 font-['Poppins', sans-serif] text-white font-light">
            <li><a href="/">Home</a></li>
            <li><a href="/">Discover</a></li>
            <li><a href="/">Creators</a></li>
            <li><a href="/">Marketplace</a></li>
        </ul>
    </div>
    <!---->
    <div class="flex mr-[30px] text-white font-medium items-center" id="cnw">
        <button class="border border-white p-2 mr-[5px] md:mr-[5px] lg:mr-[0px]" id="btn1">
            Connect Wallet
            <span>
                <i class="las la-arrow-right transform: rotate-[-20deg]"></i>
            </span>
        </button>
        <div class="lg:hidden cursor-pointer" bind:this={open}>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M4 8h16M4 16h16" />
              </svg>
        </div>
    </div>
</header>

<div class="bg-white z-[999] fixed top:0; h-[100%] w-full mt-[-150px] lg:hidden hidden" bind:this={board} id="tranmenu">
    <div class="mt-[30px]">
        <div class="text-right">
            <div class="mr-[30px] text-red-700 text-[30px] font-[bold]" bind:this={close}>
                <i class="las la-window-close"></i>
            </div>
        </div>

        <div class="mt-[150px]">
            <center>
                <ul class="text-black space-y-12 text-[20px]" id="cnw">
                    <li>
                        <a href="/">
                            <i class="las la-campground"></i>
                            Home
                        </a>
                    </li>
                    <li>
                        <a href="/">
                            <i class="las la-broadcast-tower"></i>
                            Discover
                        </a>
                    </li>
                    <li>
                        <a href="/">
                            <i class="las la-folder"></i>
                            Creators
                        </a>
                    </li>
                    <li>
                        <a href="/">
                            <i class="las la-chart-bar"></i>
                            Marketplace
                        </a>
                    </li>
                </ul>
            </center>
        </div>
    </div>
</div>