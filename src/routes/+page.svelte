<div class="head">
    <div class="content">
        <div class="title">
            <h1>Race to the Stars</h1>
            <div class="quickinfo">
                <p>2023</p>
                <span class="bar">|</span>
                <div class="rating">
                    TV-14
                </div>
                <span class="bar">|</span>
                <p>2h 21m</p>
                <span class="bar">|</span>
                <p>Action & Adventure</p>
            </div>
            <div class="desc">
                <p>
                    Two ambitious nations find themselves in a military fueled race to the final frontier. This true story follows the United States and Soviet Union through the Space Race. 
                </p>
            </div>
            <p class="staring">
                <span class="label">Starring:</span> Chris Pratt, Albert, Nancy Pelosi
            </p>
        </div>
        
    </div>
    <div class="episodes">
        <h2>Episodes</h2>
        <div class="episodesButton">
            <div class="button">
                <p>Season 1 </p>
                <svg xmlns="http://www.w3.org/2000/svg" height="32" viewBox="0 -960 960 960" width="32"><path d="M480-345 240-585l43-43 197 198 197-197 43 43-240 239Z" fill="#ffffff"/></svg>
            </div> 
        </div>
        
        <div class="episodeCardHolder">
            <div class="episodeCard">
                <img src="sputnik.jpg" alt="Sputnik 1 Space Craft"/>
                <h3>Sputnik 1</h3>
                <p>The soviets make the first move in this complex game of chess. With the United States hot on their tail, the soviets must act fast or lose their early race lead.</p>
            </div>
            <div class="episodeCard">
                <img src="vostok.webp" alt="Sputnik 1 Space Craft"/>
                <h3>Vostok 1</h3>
                <p>The Soviets retain their lead, launching the first man into space. The United States still fights to catch up but the race is looking Bleaker and Bleaker to the American people.</p>
            </div>
            <div class="episodeCard">
                <img src="freedom.jpg" alt="Sputnik 1 Space Craft"/>
                <h3>Freedom 7</h3>
                <p>With the United States badly beaten by the soviets, it would take a miracle for them to claim the space race crown.</p>
            </div>
            <div class="episodeCard">
                <img src="apollo12.webp" alt="Sputnik 1 Space Craft"/>
                <h3>Apollo 12</h3>
                <p>Only a few years after the President's speech, the space race dramatically changes, leading to the United States victory over the final frontier.</p>
            </div>
        </div>
    </div>
</div>

<style>
    .head {
        background-image: url("/launch.jpg");
        width: 100%;
        height: 100vh;
        background-size: cover;
    }
    .content {
        width: 100%;
        height: 100%;
        background: linear-gradient(90deg, rgb(32, 32, 32), rgb(32,32,32) 30%, transparent);
        display: flex;
        align-items: center;
        justify-content: start;
    }
    .title {
        width: 25%;
        margin-left: 5%;
        display: flex;
        flex-direction: column;
    }
    .title h1 {
        margin: 0px;
    }
    .quickinfo {
        display: flex;
        flex-direction: row;
        font-size: 16px;
        margin-top: 16px;
        letter-spacing: 0;
        justify-content: start;
        align-items: center;
        color: #a3a3a3
    }
    .quickinfo p {
        margin: 0px;
    }
    .quickinfo .bar {
        margin-top: 16px;
        all: unset;
        min-height: 1.5vh;
        height: 100%;
        margin-left: 7px;
        margin-right: 7px;
        color: #a3a3a3;
        margin: 0 4px;
    }
    .rating {
        border: 1px solid #a1a1a1;
        padding: 1px 2px;
    }
    .desc p {
        color: #fff;
        font-size: 16px;
        font-weight: 400;
        line-height: 22px;
        max-width: 100%;
    }
    .label {
        color: #a3a3a3;
    }
    .episodes {
        background: rgb(32, 32, 32);
        display: flex;
        flex-direction: column;
        padding: 20px 5%
    }
    .episodesButton {
        display: flex;
        cursor: pointer;
    }
    .episodesButton .button {
        display: flex;
        align-items: center;
        color: white;
        border: 1px solid white;
    }
    .episodesButton .button p {
        margin: 0px 10px;
    }
    .episodeCardHolder {
        display: flex;
        flex-direction: row;
        width: 100%;
    }
    .episodeCard {
        flex: 1 1 0px;
        padding: 20px;
        flex-grow: 2;
    }
    .episodeCard img {
        width: 100%;
        aspect-ratio: 16/9;
    }
</style>