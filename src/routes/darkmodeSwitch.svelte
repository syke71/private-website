<script>
    function toggle() {
        window.document.body.classList.toggle('dark-mode')
    }
</script>

<button id="button" on:click={toggle} />
    
<style>
    #button {
        float: right;
        display: block;
        overflow: hidden;
        background-color: #343A40;
        color: white;
        text-align: center;
        padding: 16px 16px;
    }

    #button:hover {
        background-color: #ddd;
        color: black;
    }

    :global(body.dark-mode) #button {
        background-color: #212529;
        color: white;
    }

    :global(body) {
		background-color: #f2eee2;
		transition: background-color 0.3s;
	}
	:global(body.dark-mode) {
		background-color: #1d3040;
		color: #bfc2c7;
	}
</style>