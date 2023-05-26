<link src="https://assets.nflxext.com/ffe/siteui/fonts/netflix-sans/v3/NetflixSans_W_Rg.woff2" rel="stylesheet">
<link src="https://assets.nflxext.com/ffe/siteui/fonts/netflix-sans/v3/NetflixSans_W_Md.woff2" rel="stylesheet">

<title>Watch Race to the Stars</title>
<div class="wrap">
    <div class="nav">
            <div class="logoWrap">
                <a href="/">
                    <img src="logo.svg" alt="netflix-logo">
                </a>
            </div>

            <div class="buttons">
                <a href="/join" class="joinbutton">JOIN NOW</a>
                <a href="/login" class="signinbutton">SIGN IN</a>
            </div>
    </div>
    <div>
        <slot/>
    </div>
</div>


<style>
    @font-face {
        font-family: "Netflix Sans";
        src: url("https://assets.nflxext.com/ffe/siteui/fonts/netflix-sans/v3/NetflixSans_W_Rg.woff2")
    }
    :global(body) {
        padding: 0px;
        margin: 0px;
        font-family: Netflix Sans,Helvetica Neue,Segoe UI,Roboto,Ubuntu,sans-serif;
        color: #f1f1f1;
        -webkit-text-size-adjust: 100%;
    }
    .nav {
        width: 100%;
        height: 56px;
        background: black;
        padding-left: 3%;
        padding-right: 3%;
        display: flex;
        align-items: center;
        flex-direction: row;
        box-sizing: border-box;

    }
    .logoWrap {
        fill: #e50914;
        display: inline-block;
        text-decoration: none;
        vertical-align: middle;
    }
    .nav img {
        width: 110px;
        height: 40px;
        vertical-align: middle;
    }
    .buttons {
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: end;
    }
    .buttons a {
        cursor: pointer;
    }
    .buttons .signinbutton {
        font-size: 13px;
        padding: 9px 12px;
        border: 1px solid #888;
        border-radius: 2px;
        color: #fff;
        font-weight: 400;
        line-height: 13px;
        white-space: nowrap;
        text-decoration: none;
        margin: 0 0 0 8px;
    }
    .buttons .joinbutton {
        font-size: 13px;
        padding: 9px 12px;
        border: 1px solid #e50914;
        background: #e50914;
        border-radius: 2px;
        color: #fff;
        font-weight: 400;
        line-height: 13px;
        white-space: nowrap;
        text-decoration: none;
        margin: 0 0 0 8px;
    }
</style>