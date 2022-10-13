<template>
    <section>
        <div class="container">
            <div class="feature">

                <div class="col1">
                    <div class="head">
                        <h2>Featured This Week</h2>
                        <a @click="scrollToTop">View All</a>
                    </div>

                    <div class="swiper feature-swipe">
                        <div class="swiper-wrapper">

                            <div class="swiper-slide">
                                <div class="features-img">
                                    <img src="../assets/dragon.webp" alt="">
                                </div>
                                <div class="features-caption">
                                    <h2>The Rage of Dragons</h2>
                                    <p>By Evan Winter</p>
                                    <div class="price">
                                        <span>$50.00</span>
                                    </div>
                                    <div class="review">
                                        <div class="rating">
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star-half-o"></i>
                                        </div>
                                        <p>(120 Review)</p>
                                    </div>
                                    <a href="book-details.html" class="border-btn">View Details</a>
                                </div>
                            </div>

                            <div class="swiper-slide">
                                <div class="features-img">
                                    <img src="../assets/dragon.webp" alt="">
                                </div>
                                <div class="features-caption">
                                    <h2>The Rage of Dragons</h2>
                                    <p>By Evan Winter</p>
                                    <div class="price">
                                        <span>$50.00</span>
                                    </div>
                                    <div class="review">
                                        <div class="rating">
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star checked"></i>
                                            <i class="fa fa-star-half-o"></i>
                                        </div>
                                        <p>(120 Review)</p>
                                    </div>
                                    <a href="book-details.html" class="border-btn">View Details</a>
                                </div>
                            </div>

                        </div>

                        <div class="swiper-button-prev"></div>
                        <div class="swiper-button-next"></div>
                    </div>
                </div>

                <div class="col2">
                    <div class="google-add">
                        <img src="../assets/joker.webp" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    mounted() {
        new Swiper(".feature-swipe", {
            loop: true,
            speed: 400,
            slidesPerView: 1,
            slidesPerGroup: 1,
            autoplay: {
                delay: 3000,
            },
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            }
        })
    },
    methods: {
    scrollToTop: function () {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>



<style scoped>
@media (min-width: 1400px) {
    .container {
        max-width: 1350px;
    }
}

section {
    padding-top: 120px;
}

.feature {
    display: grid;
    grid-template-columns: 75% 25%;
    gap: 24px;
}

.col1 .head {
    display: flex;
    justify-content: space-between;
    margin-bottom: 40px;
}

.head h2 {
    font-family: "Playfair Display", serif;
    font-weight: 700;
}

.head a{
    color: #1a1a1a;
    font-weight: 500;
    font-size: 16px;
    text-decoration:none;
    border-bottom:2px solid #eee1e0;
    margin-top: 11px;
    cursor: pointer;
    
}

.swiper-slide {
    display: flex;
    padding: 31px 80px;
    background-color: #FF1616;
}

.features-caption {
    font-family: "Playfair Display", serif;
    align-self: center;
    margin-left: 50px;
    color: #fff;
}

.features-caption .price span {
    font-family: "Roboto", sans-serif;
    font-size: 32px;
    font-weight: 500;
    padding-top: 50px;
}

.features-caption h2 {
    font-size: 40px;
}

.review {
    display: flex;
    gap: 10px;
    padding-bottom: 20px;
}

.review p {
    padding: 19px 0px;
}

.rating .checked {
    color: #fff;
}

.features-caption a {
    color: #fff;
    text-decoration: none;
    border: 1px solid #fff;
    padding: 18px 42px;
    border-radius: 50px;
}

.rating .fa {
    font-size: 20px;
    padding: 20px 5px;
}

.col2 {
    height: 575;
}

.swiper-button-next{
    color: rgba(255,255,255,0.3);
    transition: all 0.3s ease;
}

.swiper-button-next:hover{
    color:#fff;
}

.swiper-button-prev{
    color: rgba(255,255,255,0.3);
    transition: all 0.3s ease;
}

.swiper-button-prev:hover{
    color:#fff;
}
</style>