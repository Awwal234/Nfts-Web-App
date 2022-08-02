<svelte:head>
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
</svelte:head>

<script>
	import '../app.css';
</script>

<style>
    #createtext{
        font-family:'Poppins', sans-serif;
    }
</style>

<div class="mt-[100px] md:mt-[180px] lg:mt-[250px] p-4 md:ml-[30px] md:mr-[30px] ml-[10px] mr-[10px]">
    <div class="md:text-[30px] text-orange-500 w-fit pb-2 border-b-2 border-orange-500" id="createtext">
        Create and Sell your NFTs
    </div>

    <!---->
    <center>
        <div class="mt-[30px] md:mt-[50px] md:w-[100%] md:inline-flex md:flex-wrap md:p-4 mx-auto justify-center space-y-4 md:space-x-8 md:space-y-0 lg:space-y-0">
            <!--create and sell1-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:ml-[30px] lg:ml-[0px]">
                <div class="mx-auto text-[30px] font-bold">
                    <i class="las la-wallet"></i>
                </div>
                <div class="mx-auto md:text-[15px] mt-[10px] font-bold text-indigo-900">
                    Setup your Wallet
                </div>
                <div class="mt-[15px] mx-auto text-center text-[13px]" id="createtext">
                    Set up your Tezos Wallet, connect it to NftsHot by 
                    clicking the wallet icon in the top right corner. Ready 
                    to buy and sell lets go!!.
                </div>
            </div>
            <!--create and sell2-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4">
                <div class="mx-auto text-[30px] font-bold">
                    <i class="las la-copy"></i>
                </div>
                <div class="mx-auto md:text-[15px] mt-[10px] font-bold text-indigo-900">
                    Create your Collection
                </div>
                <div class="mt-[15px] mx-auto text-center text-[13px]" id="createtext">
                    Create and set up your collection. Add social links, 
                    a description, profile & banner images, and set a
                    secondary sales fee.
                </div>
            </div>
            <!--create and sell3-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:top-[20px] lg:top-[0px] relative">
                <div class="mx-auto text-[30px] font-bold">
                    <i class="las la-cloud-upload-alt"></i>
                </div>
                <div class="mx-auto md:text-[15px] mt-[10px] font-bold text-indigo-900">
                    Add your NFTs
                </div>
                <div class="mt-[15px] mx-auto text-center text-[13px]" id="createtext">
                    Upload your work, add a title and description, and 
                    customize your NFTs with properties, stats, and 
                    unlockable content. You can!
                </div>
            </div>
            <!--create and sell4-->
            <div class="w-[90%] md:w-[35%] lg:w-[20%] h-fit bg-slate-900 rounded-lg p-4 md:top-[20px] lg:top-[0px] relative">
                <div class="mx-auto text-[30px] font-bold">
                    <i class="las la-exchange-alt"></i>
                </div>
                <div class="mx-auto md:text-[15px] mt-[10px] font-bold text-indigo-900">
                    List them for Sale
                </div>
                <div class="mt-[15px] mx-auto text-center text-[13px]" id="createtext">
                    Do you own a bunch of digital assets you want to 
                    sell ? feel free to list them we help you sell 
                    them quick!. And start your earning.
                </div>
            </div>
            <!--end create and sell-->
        </div>
    </center>
</div>