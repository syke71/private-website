<script>
	import Navbar from './navbar.svelte';
	import BackgroundImg from './backgroundImg.svelte';
    import Footer from './footer.svelte';
    import '../lib/summary.css';

    import { fade } from 'svelte/transition'

    export let data

</script>

<BackgroundImg />

<div class="layout">
    
    {#key data.pathname}
        <div
            in:fade={{ duration: 300, delay: 400 }}
            out:fade={{ duration: 300 }}
        >
            <slot />
        </div>
    {/key}
    
    <Footer />
    
       
</div>

<Navbar />


<style>
	@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400&display=swap');
    :global(body) {
        background-color: #212529;
        color: white;
		font-family: 'Raleway', sans-serif;
    }

    :root {
        --layout-color: #fd5e53;
    }

    .layout {
        position: relative;
        top: 25em;
        /* border: 2px solid red; */

        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        justify-content: space-evenly;
        max-width: 45em;
        margin: auto;
    }

</style>