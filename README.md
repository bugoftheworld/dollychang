<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>

    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="./css/profolio.css">


</head>

<body>

    <div class="header">
        <div class="logo">
            <img src="img/logo.svg">
        </div>
    </div>

    <div class="content  animated fadeIn">
        <div class="carousel owl-carousel">
            <div>
                <img src="img/carousel1.png">
            </div>
            <div>
                <img src="img/carousel2.png">
            </div>
            <div>
                <img src="img/carousel3.png">
            </div>
            <div>
                <img src="img/carousel4.png">
            </div>
            <div>
                <img src="img/carousel5.png">
            </div>
        </div>

        <div class="part">
            <div class="title">
                <span>ABOUT ME<img src="img/title1.svg"></span>
            </div>
            <div class="article">
                <p>1988/12/5</p>
                <p>工作經歷 / 六年</p>
                <p class="right">Acer宏碁電子股份有限公司　設計專員</p>
                <p class="right">神通光通信股份有限公司　 UI/ 前端設計工程師</p>
                <p>語言能力 / 中文、英文</p>
                <p>聯絡方式 / dollychang5158@gmail.com</p>
            </div>
        </div>
        <div class="part">
            <div class="title">
                <span>SKILL<img src="img/title2.svg"></span>
            </div>
            <div class="article">
                <p>design</p>
                <p class="right">(ui / illustrator / photoshop / after effect / blender / zeplin / invesion / figma / adobe XD)</p>
                <p>front end enginer </p>
                <p class="right">(html / css / scss / sass / jquery / javascript / git / bootstrap)</p>
            </div>
        </div>
    </div>
    <div class="footer">
        <div>copy righting by dolly 2019</div>
        <div class="linkLogo">
            <a target="_blank" href="https://www.linkedin.com/in/pei-wen-chang-47b3b8165/">
            <img src="img/liIcon.svg" alt="Linkedin">
            </a>
            <a target="_blank" href="https://www.behance.net/dollychang">
            <img src="img/beIcon.svg" alt="Behance">
            <a>
        </div>
    </div>

</body>


<script src="js/jquery.min.js"></script>
<script src="js/owl.carousel.min.js"></script>

<script>
    $(
        $('.owl-carousel').owlCarousel({
            loop: true,
            margin: 0,
            nav: true,
            dot: false,
            lazyLoad: true,
            responsive: {
                0: {
                    items: 1
                },
                600: {
                    items: 1
                },
                1000: {
                    items: 1
                }
            }
        }))
</script>
