    
    <style>
    body {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    text-align: center;
}

body:before {
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    opacity: .1;
    z-index: -1;
    content: "";
    position: fixed;
    background: url(https://api.mmcee.cn/acgimg/acgurl.php) center/cover;
}

.box,
.box-header {
    display: inline-block;
    position: relative;
    vertical-align: middle;
    width: 500px;
    height: 300px;
    border-radius: 20px;
    transition: 0.2s ease;
    margin: 1rem;
}

.box img,
.box-header img {
    background-repeat: no-repeat;
    background-origin: content-box;
    background-size: cover;
    width: 100%;
    height: 100%;
    border-radius: 20px;
    background-size: cover;
    object-fit: cover;
}

.box:hover,
.box-header:hover {
    transform: scale(1.1);
}

.box:active,
.box-header:active {
    transform: scale(0.9);
}

.box-header {
    width: 100%;
    max-width: 1045px;
    height: 210px;
}

.cover {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    border-radius: 20px;
}

.cover-color-1 {
    background-image: linear-gradient( 297deg, rgb(160 156 156 / 55%), rgb(226 149 64));
}

.cover-color-2 {
    background-image: linear-gradient( 297deg, rgb(160 156 156 / 55%), rgb(90 62 121));
}

.cover-color-3 {
    background-image: linear-gradient( 297deg, rgb(160 156 156 / 55%), rgb(26 67 133));
}

.cover-color-4 {
    background-image: linear-gradient( 297deg, rgb(160 156 156 / 55%), rgb(3 169 244));
}

.cover-color-5 {
    background-image: linear-gradient( 297deg, rgb(160 156 156 / 55%), rgb(201 181 166));
}

.cover-content {
    top: 30px;
    left: 0;
    right: 0;
    position: absolute !important;
    max-width: 100%;
    padding: 20px;
    color: #f5f5f5;
    text-align: left;
}

.cover-content-header {
    top: 0;
    left: 0;
    right: 0;
    position: absolute !important;
    max-width: 100%;
    padding: 20px;
    color: #f5f5f5;
    text-align: left;
}

.cover-content img,
.cover-content-header img {
    width: 80px;
    height: 80px;
    border-radius: 50px;
}

.container {
    max-width: 1101px;
    text-align: center
}

@media screen and (max-width:1101px) {
    body {
        height: auto;
    }
    .box,
    .box-header {
        width: 90%;
    }
    .box {
        height: 260px;
    }
    .cover-content {
        top: 0;
    }
    .cover-content h1 {
        font-size: 1.8rem;
    }
    .cover-content img,
    .cover-content-header img {
        width: 60px;
        height: 60px;
    }
    .box:hover,
    .box-header:hover {
        transform: unset;
    }
    .box:active,
    .box-header:active {
        transform: unset;
    }
}

@media screen and (max-height:888px) {
    body {
        height: auto;
    }
}
    </style>
    <div class="container">
        <div class="box-header">
            <div class="cover cover-color-1"></div>
            <img src="./img/bk-1.jpg">
            <div class="cover-content-header">
                <img src="./img/logo-2.jpg" alt="">
                <h1>Erhecy's Index</h1>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="box">
            <a href="https://www.mmcee.cn" target="_blank" rel="noopener noreferrer">
                <div class="cover cover-color-2"></div>
                <img src="./img/bk-2.jpg">
                <div class="cover-content ">
                    <img src="./img/logo-1.ico" alt="">
                    <h1>MineCraft爱好者</h1>
                </div>
            </a>
        </div>
        <div class="box">
            <a href="https://blog.mmcee.cn" target="_blank">
                <div class="cover cover-color-3"></div>
                <img src="./img/bk-3.jpg">
                <div class="cover-content ">
                    <img src="./img/logo-2.jpg" alt="">
                    <h1>Blog</h1>
                </div>
            </a>
        </div>
        <div class="box">
            <a href="https://github.com/ERHECY" target="_blank">
                <div class="cover cover-color-4"></div>
                <img src="./img/bk-4.jpg">
                <div class="cover-content ">
                    <img src="./img/logo-3.png" alt="">
                    <h1>GitHub</h1>
                </div>
            </a>
        </div>
        <div class="box">
            <div class="cover cover-color-5"></div>
            <img src="./img/bk-5.jpg">
            <div class="cover-content ">
                <img src="./img/logo-4.png" alt="">
                <h1>More……</h1>
            </div>
        </div>
    </div>
