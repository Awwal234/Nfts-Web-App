<svelte:head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
    <link rel="icon" href="img/guard.png">
    <title>NftsHot Place-orders</title>
</svelte:head>

<script>
	import '../app.css';
    import {onMount} from 'svelte';
    import { fly } from 'svelte/transition';

    let True = true;

    // @ts-ignore
    let abort;
    onMount(() => {
        // @ts-ignore
        abort.onclick = function () {
            location.href='/';
        }
    })
</script>

<style>
    body{
        background:#000;
    }
    #potext{
        font-family:'Poppins', sans-serif;
    }
    #cent>input,#cent>button{
        font-family:'DM Sans', sans-serif;
    }
</style>

{#if True}
<body transition:fly="{{x:200, duration:1000}}">
    <center>
        <div class="mx-auto mt-[100px]">
            <div class="w-[90%] md:w-[70%] lg:w-[40%] bg-slate-800 p-[6px] text-left rounded-xl">
                <div class="float-right">
                    <div class="item-center bg-orange-800 item-center cursor-pointer w-[30px] mt-[-16px] mr-[-20px] h-[30px] p-[10px] rounded-full hover:opacity-90">
                        <div class="text-white font-bold text-[14px] mt-[-7px]" bind:this={abort}>&times</div>
                    </div>
                </div>
                <div id="potext" class="mt-[20px] text-white">
                    <center>
                        <div class="md:text-[25px] text-[20px]" id="potext">Place Order</div>
                    </center>
                </div>
                <div class="mt-[20px] p-[10px]">
                    <center id="cent">
                        <input type="number" class="p-[5px] w-[90%] text-white bg-transparent rounded-lg border border-gray-200 focus:outline-none" name="quantity nfts" placeholder="Enter quantity">
                        <button class="mt-[17px] text-white bg-orange-800 w-[90%] p-[6px] rounded-lg hover:opacity-80">
                            Place Order
                        </button>
                    </center>
                </div>
            </div>
        </div>
    </center>
</body>
{/if}