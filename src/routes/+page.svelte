<div id="orb-container">
    <img class="logo" draggable="false" src="/wavedream.svg" alt="WaveDream.Space" />
    <img class="title" draggable="false" src="/wavedream_title.svg" alt="WaveDream.Space" />

        <div id="button-div" class="w-screen h-40 mt-[35vh] flex justify-center">
        <div id="buttons" class="w-[60vh] flex items-center justify-evenly">
            <a href="/learn">
                <button class="btn btn-sm btn-secondary btn-outline rounded-full tracking-widest px-6">
                    Learn
                </button>
            </a>
            <a href="/create">
                <button class="btn btn-normal btn-primary btn-outline rounded-full tracking-widest">
                    Create
                </button>
            </a>
            <a href="/explore">
                <button class="btn btn-sm btn-secondary btn-outline rounded-full tracking-widest">
                    Explore
                </button>
            </a>
        </div>
    </div>


</div>

<!-- //Styling  -->
<style lang="postcss">
#orb-container {
    width: 100vw;
    height: 100vh;
    background: radial-gradient(circle at center, rgb(7, 0, 21), hsl(254, 89%, 10%) 20%, black 100%);
    position: fixed;
    display: flex;
    flex-direction: column;
    top: 0;
    left: 0;
    justify-content: center;
    align-items: center;
}

.logo {
    margin-top: -25vh;
    position: absolute;
    width: 50vh;
    height: 50vh;
    -moz-user-select: -moz-none;
    -khtml-user-select: none;
    -webkit-user-select: none;
    -o-user-select: none;
    user-select: none;
}

.title {
    margin-top: 15vh;
    width: 60vh;
    position: absolute;
}

</style>