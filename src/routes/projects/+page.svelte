<script>
    import japaneseFlag from "../../public/assets/japaneseFlag.png";
    import southKoreanFlag from "../../public/assets/southKoreanFlag.png";
    import swedishFlag from "../../public/assets/swedishFlag.png";
    import flagMix from "../../public/assets/flags.png";
</script>

<div class="projects-container">
    <ul>
        <li><h1>Language Projects</h1></li>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <li><h1>CS Projects</h1></li>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <li><h1>Other Projects</h1></li>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </ul>
    <span class="image-container">
        <!-- <img src={ japaneseFlag } alt='Flag-1' />
        <img src={ southKoreanFlag } alt='Flag-2' />
        <img src={ swedishFlag } alt='Flag-3' /> -->
        <img src={ flagMix } alt='Flags' />
    </span>
    
    
</div>


<style>
    .projects-container {
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        max-width: 45em;
    }

    .projects-container ul {
        position: relative;
        width: fit-content;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        border: 2px solid red;
        max-width: 60%;
    }

    .projects-container li {
        list-style: none;
        margin-bottom: 1em;
    }

    .projects-container h1 {
        font-size: 26px;
        text-decoration: underline;
        text-underline-offset: 8px;
        text-decoration-color: #525252;
        text-decoration-thickness: 5px;

        
    }

    .image-container {
        border: 2px solid red;
        position: relative;
        object-position: center;
        max-width: 40%;
    }

    .image-container img {
        width:100%;
    }

</style>