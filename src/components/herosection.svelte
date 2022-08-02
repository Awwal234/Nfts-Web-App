<svelte:head>
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
</svelte:head>

<script>
	import '../app.css';
</script>

<div class="flex flex-col-reverse md:flex-col-reverse lg:flex-row w-100% mt-[150px] lg:mt-[150px] p-4 lg:justify-between">
    <div class="lg:w-[40%] md:w-[70%] w-[70%] text-white ml-[30px]">
        <div class="md:text-[50px] text-[30px] font-medium font-['Poppins', sans-serif]">
            Discover Rare Collections
            Of <span class="text-orange-700">NFTs</span> by <span class="text-orange-500">Class Artists.</span>
        </div>
        <div class="mt-[15px] font-light font-['Poppins', sans-serif]">
            Every digital artwork on Nftshot is authentic
            and truly unique. The Blockchain technology makes the
            new approach to digital ownership possible.
        </div>
        <div class="space-x-3 md:space-x-4 mt-[25px] flex font-medium font-['Poppins', sans-serif]">
            <button class="bg-gradient-to-r from-orange-700 to-orange-900 py-[8px] px-[10px] rounded-sm hover:opacity-90">
                Explore Marketplace
            </button>
            <!---->
            <button class="hover:opacity-90">
                <span>
                    <i class="las la-video"></i>
                </span>
                How it works
            </button>
        </div>
    </div>
    <!---->
    <div class="mx-auto md:justify-content w-[80%] md:h-[100%] md:w-[70%] lg:w-[30%] lg:text-left md:mx-auto lg:mr-[70px]">
        <div>
            <img src="img/nftimage.png" class="w-[90%] h-[100%] md:w-[90%] lg:w-[100%] mx-auto rounded-md" alt=""/>
        </div>
    </div>
</div>

<!---->
<!--goto button-->
<div class="mt-[30px] md:mt-[60px] mr-[60px] cursor-pointer">
    <a href="#liveftext">
    <div class="w-[40px] h-[40px] rounded-full p-2 border border-white flex shadow-sm shadow-white float-right hover:transition-all hover:text-orange-600">
        <i class="las la-long-arrow-alt-down mx-auto"></i>
    </div>
    </a>
</div>