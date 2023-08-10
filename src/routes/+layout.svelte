<script>
	import Navbar from './navbar.svelte';
	import BackgroundImg from './backgroundImg.svelte';
    import Footer from './footer.svelte';
</script>

<BackgroundImg />

<div class="layout">
    

    <slot />
    
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