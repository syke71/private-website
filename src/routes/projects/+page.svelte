<script>
    import japaneseFlag from "../../public/assets/japaneseFlag.png";
    import southKoreanFlag from "../../public/assets/southKoreanFlag.png";
    import swedishFlag from "../../public/assets/swedishFlag.png";
    import flagMix from "../../public/assets/flags.png";
</script>

<div class="project-container">
    <div>
        <span class="project-text-container">
            <li><h1>Language Projects</h1></li>
            <p>Language learning started originally as a hobby back in high school. Initially, it was a challenge I set for myself, but it quickly grew to become very enjoyable.</p>
            <p>I had already learned English and to a lesser extent, French, in the past. However, Japanese was the first language I chose to learn purely for the joy of it. My focus in this section will be on Japanese and upcoming languages like Korean and Swedish. I'll share the process, challenges I faced, and the milestones I've achieved and still aim for.</p>
        </span>
        <span class="project-image-container">
            <img src={ flagMix } alt='Flags' />
        </span>
    </div>
    <div>
        <span class="project-text-container">
            <li><h1>CS Projects</h1></li>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </span>
        <span class="project-image-container">
            <img src={ flagMix } alt='Flags' />
        </span>
    </div>
    <div>
        <span class="project-text-container">
            <li><h1>Other Projects</h1></li>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </span>
        <span class="project-image-container">
            <img src={ flagMix } alt='Flags' />
        </span>
    </div>
</div>



<style>
    .project-container {
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-width: 45em;
    }

    .project-container div {
        margin: 0;
        padding: 0;
        margin-bottom: 8vh;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        /* border: 2px solid red; */
    }

    .project-text-container {
        max-width: 60%;
        padding-right: 5%;
    }

    .project-text-container h1 {
        font-size: 26px;
        text-decoration: underline;
        text-underline-offset: 8px;
        text-decoration-color: #ac46a1;
        text-decoration-thickness: 5px;
    }
    .project-text-container li {
        list-style: none;
        margin-bottom: 1em;
    }

    .project-container span {
        /* border: 2px solid red; */
    }

    .project-image-container {
        max-width: 40%;
    }

    .project-image-container img {
        width:100%;
    }


</style>