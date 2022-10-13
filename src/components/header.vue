<template>
    <div class="header">
        <div class="container">
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Categories</a></li>
                    <li><a href="#">About</a></li>
                    <li class="drop"><a href="#">Pages</a>
                        <ul class="submenu">
                            <li><a href="#">login</a></li>
                            <li><a href="#">Cart</a></li>
                            <li><a href="#">Checkout</a></li>
                            <li><a href="#">Book Details</a></li>
                            <li><a href="#">Blog Details</a></li>
                            <li><a href="#">Element</a></li>
                        </ul>
                    </li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Contect</a></li>
                </ul>
            </nav>
        </div>
    </div>
    <div class="main">
        <div class="banner">
            <div class="container">

                <!-- swiper -->
                <div class="swiper header-swiper">
                    <div class="swiper-wrapper">

                        <div class="swiper-slide">
                            <div class="image1">
                                <div class="container h-100">
                                    <div class="text-main">
                                        <div class="caption">
                                            <span>Science Fiction</span>
                                            <h1>The History<br> of Phipino</h1>
                                            <button><a href="#">Browse Store</a></button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="swiper-slide">
                            <div class="image2">
                                <div class="container h-100">
                                    <div class="text-main">
                                        <div class="caption">
                                            <span>Science Fiction</span>
                                            <h1>The History<br> of Phipino</h1>
                                            <button><a href="#">Browse Store</a></button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="swiper-slide">
                            <div class="image3">
                                <div class="container h-100">
                                    <div class="text-main">
                                        <div class="caption">
                                            <span>Science Fiction</span>
                                            <h1>The History<br> of Phipino</h1>
                                            <button><a href="#">Browse Store</a></button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="swiper-pagination"></div>

                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    mounted() {
        new Swiper(".header-swiper", {
            loop: true,
            speed: 1000,
            slidesPerView: 1,
            slidesPerGroup: 1,
            autoplay: {
                delay: 5000,
                waitForTransition: true,
                disableOnInteraction: false,
            },
            effect: 'fade',
            fadeEffect: {
                crossFade: true
            },
            pagination: {
                el: '.swiper-pagination',
                clickable: true,
                type: "bullets",
            },
        })
    },
}

window.addEventListener('scroll', function () {
    if (document.documentElement.scrollTop > 300) {
        document.querySelector('.header').classList.add('fixed-top');

    } else {
        document.querySelector('.header').classList.remove('fixed-top');
        document.body.style.paddingTop = '0';
    }
});

</script>
    



<style scoped>
.fixed-top {
    position: fixed;
    background-color: #FEF4F4;
    animation: 300ms ease-in-out 0s normal none 1 running fadeInDown;
    box-shadow: 0 10px 15px rgb(25 25 25 / 10%);
}

.header {
    background-color: #FEF4F4;
}

@keyframes fadeInDown {
    0% {
        opacity: 0;
        transform: translateY(-20px);
    }

    100% {
        opacity: 1;
        transform: translateY(0);
    }
}

.header nav ul ul.submenu {
    display: none;
    position: absolute;
    top: auto;
    margin-top: 16px;
    padding: 5px 0 10px 0;
    background: #fff;
    width: 160px;
    box-shadow: 0 0 10px 3px rgb(0 0 0 / 5%);
    border-radius: 5px 5px 0 0;
    text-align: left;
    font-family: 'Roboto', sans-serif;
    transition: all .3s ease-out 0s;
}

.submenu li>a:hover {
    color: #ff1616;
    transition: all .3s ease-out 0s;
    letter-spacing: .5px;
}

.header ul li.drop:hover .submenu {
    display: block;
    z-index: 2;
}

.submenu>li>a {
    padding-left: 20px;
    font-size: 14px;
    color: #0b1c39;
    text-transform: capitalize;
}

.header nav ul ul.submenu li {
    padding: 0;
    display: block;
    margin: 6px 0;
}

.main {
    background-color: #FEF4F4;
}

ul {
    text-align: center;
    padding-left: 0;
    margin-bottom: 0;
}

.header nav ul li {
    font-weight: 500;
    display: inline-block;
    list-style: none;
    padding: 15.5px 17px;
    margin: 0 4px;
}

a {
    color: #232F55;
    text-decoration: none;
}

.header .container a:hover {
    color: red;
}

.swiper-slide .image1 {
    background-image: url("../assets/banner.webp");
    height: 580px;
    width: 100%;
}

.swiper-slide .image2 {
    background-image: url("../assets/banner0.webp");
    height: 580px;
    width: 100%;
}

.swiper-slide .image3 {
    background-image: url("../assets/banner2.webp");
    height: 580px;
    width: 100%;
}

.container .text-main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.container .text-main .caption {
    color: #fff;
    text-align: center;
    animation: fadein 2s;
}

.swiper-slide .image2 .caption span,h1{
    animation: fadein 2s;
}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

.container .text-main .caption h1 {
    font-family: "Playfair Display", serif;
    font-size: 60px;
    font-weight: 400;
    padding-bottom: 34px;
    color: #fff;
    line-height: 1.2;
}

.caption span {
    font-size: 14px;
    line-height: 1.2;
    font-weight: 300;
    color: #1a1a1a;
    margin-bottom: 20px;
    display: inline-block;
    background: #fff;
    padding: 6px 17px;
    border-radius: 17px;
}

.caption button {
    position: relative;
    font-size: 16px;
    border: none;
    padding: 20px 43px;
    border-radius: 50px;
    background-color: #ff1616;
    transition: all ease-in-out 250ms;
    z-index: 1;
    overflow: hidden;
}

.caption button a {
    color: white;
}

.caption button::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 0;
    border-radius: 50px;
    background-color: #cf0f0f;
    z-index: -1;
    transition: all 250ms;
}

.caption button:hover::before {
    width: 100%;
}

@media (min-width: 1400px) {
    .container {
        max-width: 1320px;
    }
}
</style>