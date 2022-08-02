<svelte:head>
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
</svelte:head>

<script>
	import '../app.css';
    import {onMount} from 'svelte';
</script>

<style scoped>
    #liveftext{
        font-family:'Poppins', sans-serif;
    }
    #ordersbtn{
        transition: 0.7s linear;
    }
</style>

<div class="mt-[100px] md:mt-[180px] lg:mt-[250px] p-4 md:ml-[30px] md:mr-[30px] ml-[10px] mr-[10px]">
    <div class="flex justify-between p-4 md:p-0">
        <div class="md:text-[30px] text-orange-500 p-0 border-b-2 border-orange-500" id="liveftext">
            Live Sales
        </div>
        <!---->
        <div class="md:text-[20px] text-orange-500" id="liveftext">
            <a href="/">
                Explore more
                <span>
                    <i class="las la-braille"></i>
                </span>
            </a>
        </div>
    </div>

    <!--the sales-->
    <center>
        <div class="mt-[30px] md:mt-[50px] md:w-[100%] md:inline-flex md:flex-wrap md:p-4 mx-auto justify-center space-y-4 md:space-x-8 md:space-y-0 lg:space-y-0">
            <!--nft 1 live sales-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:ml-[30px] lg:ml-[0px]">
                <div class="">
                    <img src="img/egypt.jpg" class="rounded-lg w-[100%]" alt=""/>
                </div>
                <div class="mt-[5px] text-center text-white" id="liveftext">Bored</div>
                <div class="text-white mt-[10px] font-normal p-1 text-[12px] flex justify-between items-center" id="liveftext">
                    <div class="w-[60%] text-left">Created by - Demon Slayer</div>
                    <div class="text-[9px] text-left">
                        <div>Current Bid</div>
                        <div class="text-orange-600 font-bold">9.09XTZ</div>
                    </div>
                </div>
                <!--btn-->
                <a href="placeorders">
                    <div class="text-center mt-[20px] p-2 font-medium">
                        <button class="bg-yellow-900 text-sm text-white p-2 rounded-full items-center hover:opacity-80 hover:bg-transparent hover:border hover:border-yellow-900" id="ordersbtn">
                            Place Orders
                            <span><i class="las la-baby-carriage text-xl"></i></span>
                        </button>
                    </div>
                </a>
            </div>
            <!--nft 2 live sales-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4">
                <div class="">
                    <img src="img/guard.png" class="rounded-lg w-[100%]" alt=""/>
                </div>
                <div class="mt-[5px] text-center text-white" id="liveftext">Guard</div>
                <div class="text-white mt-[10px] font-normal p-1 text-[12px] flex justify-between items-center" id="liveftext">
                    <div class="w-[60%] text-left">Created by - WestBoy</div>
                    <div class="text-[9px] text-left">
                        <div>Current Bid</div>
                        <div class="text-orange-600 font-bold">6.09XTZ</div>
                    </div>
                </div>
                <!--btn-->
                <a href="placeorders">
                    <div class="text-center mt-[20px] p-2 font-medium">
                        <button class="bg-yellow-900 text-sm text-white p-2 rounded-full items-center hover:opacity-80 hover:bg-transparent hover:border hover:border-yellow-900" id="ordersbtn">
                            Place Orders
                            <span><i class="las la-baby-carriage text-xl"></i></span>
                        </button>
                    </div>
                </a>
            </div>
            <!--nft 3 live sales-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:top-[20px] lg:top-[0px] relative">
                <div class="">
                    <img src="img/queen.webp" class="rounded-lg w-[100%]" alt=""/>
                </div>
                <div class="mt-[5px] text-center text-white" id="liveftext">Queen</div>
                <div class="text-white mt-[10px] font-normal p-1 text-[12px] flex justify-between items-center" id="liveftext">
                    <div class="w-[60%] text-left">Created by - Durajon D</div>
                    <div class="text-[9px] text-left">
                        <div>Current Bid</div>
                        <div class="text-orange-600 font-bold">13.09XTZ</div>
                    </div>
                </div>
                <!--btn-->
                <a href="placeorders">
                    <div class="text-center mt-[20px] p-2 font-medium">
                        <button class="bg-yellow-900 text-sm text-white p-2 rounded-full items-center hover:opacity-80 hover:bg-transparent hover:border hover:border-yellow-900" id="ordersbtn">
                            Place Orders
                            <span><i class="las la-baby-carriage text-xl"></i></span>
                        </button>
                    </div>
                </a>
            </div>
            <!--nft 4 live sales-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:top-[20px] lg:top-[0px] relative">
                <div class="">
                    <img src="img/nftimage.png" class="rounded-lg w-[100%]" alt=""/>
                </div>
                <div class="mt-[5px] text-center text-white" id="liveftext">Happy</div>
                <div class="text-white mt-[10px] font-normal p-1 text-[12px] flex justify-between items-center" id="liveftext">
                    <div class="w-[60%] text-left">Created by - SwiftLan D</div>
                    <div class="text-[9px] text-left">
                        <div>Current Bid</div>
                        <div class="text-orange-600 font-bold">20.09XTZ</div>
                    </div>
                </div>
                <!--btn-->
                <a href="placeorders">
                    <div class="text-center mt-[20px] p-2 font-medium">
                        <button class="bg-yellow-900 text-sm text-white p-2 rounded-full items-center hover:opacity-80 hover:bg-transparent hover:border hover:border-yellow-900" id="ordersbtn">
                            Place Orders
                            <span><i class="las la-baby-carriage text-xl"></i></span>
                        </button>
                    </div>
                </a>
            </div>
            <!--end nft live sales-->
        </div>
    </center>
</div>