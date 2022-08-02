<svelte:head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <link rel="icon" href="img/guard.png">
    <title>NftsHot App</title>
</svelte:head>

<script lang="ts">
	import '../app.css';
    import Header from '../components/header.svelte';
    import Hero from '../components/herosection.svelte';
    import Livesales from '../components/livesales.svelte';
    import Create from '../components/createnft.svelte';
    import Footer from '../components/footer.svelte';
    import { fly } from 'svelte/transition';

    let True = true;
</script>

{#if True}
<body class="bg-black text-white" transition:fly="{{y:200, duration:1000}}">
    <Header/>
    <div class="h-fit md:h-[fit] lg:h-[fit]">
        <Hero/>
    </div>
    <Livesales/>
    <Create/>
    <Footer/>
</body>
{/if}

