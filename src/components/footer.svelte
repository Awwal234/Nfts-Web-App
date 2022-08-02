<svelte:head>
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
</svelte:head>

<script lang="ts">
	import '../app.css';
    var newy = new Date();
    var yearly = newy.getFullYear();
</script>

<style>
    #copyr{
        font-family:'Poppins', sans-serif;
    }
</style>

<div class="mt-[40px] bg-neutral-900 w-full p-[40px]">
    <form action="/" method="post">
        <div class="mx-auto justify-center">
            <div class="w-[90%] md:w-[50%] bg-transparent flex">
                <input type="email" placeholder="Enter your mail" class="w-[70%] md:w-[70%] py-[10px] px-[4px] md:py-[20px] focus:outline-none text-slate-600">
                <button class="w-30% md:w-[30%] py-[10px] px-[4px] md:py-[20px] text-white bg-indigo-900 font-medium hover:opacity-80 hover:bg-indigo-700">
                    Subscribe
                </button>
            </div>
        </div>
    </form>

    <center class="text-[13px] font-bold mt-[20px]" id="copyr">
        <div>
            <span>
                Copyrights {yearly}, Developed By Dolapo NftsHot
            </span>
        </div>
    </center>
</div>