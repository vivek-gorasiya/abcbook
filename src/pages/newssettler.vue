<template>
    <div class="newssettler">
        <div class="container">
            <div class="wcard">
                <div class="wcard1">
                    <img src="../assets/wcard1.webp" />
                    <h2>The History
                        <br>
                        of Phipino
                    </h2>
                    <a href="#">View Details</a>
                </div>
                <div class="wcard2">
                    <img src="../assets/wcard2.webp" />
                    <h2>Wilma Mumduya
                    </h2>
                    <a href="#">View Details</a>
                </div>
            </div>

            <div class="join-form">
                <h1>
                    Join Newslettler
                </h1>
                <p>Lorem started its journey with cast iron (CI) products in 1980. The initial main objective <br> was
                    to
                    ensure pure water and affordable irrigation.</p>
                <form action="#">
                    <input type="email" placeholder="Enter your email">
                    <button type="submit">Subscribe</button>
                </form>
            </div>
        </div>
    </div>
</template>

<style scoped>
* {
    font-family: "Playfair Display", serif;
}

.newssettler {
    padding-bottom: 90px;
    background-color: #FEF4F4;
}

.wcard {
    display: flex;
    justify-content: space-between;

}

.wcard1 img {
    width: 650px;
}

.wcard2 img {
    width: 650px;
}

.wcard1 {
    position: relative;
}

.wcard2 {
    position: relative;
}

.wcard1 h2 {
    font-weight: 400;
    top: 50px;
    left: 50px;
    position: absolute;
    color: #fff;
}

.wcard2 h2 {
    font-weight: 400;
    top: 70px;
    left: 50px;
    position: absolute;
    color: #fff;
}

.wcard1 a {
    background: #ff1616;
    font-family: "Roboto", sans-serif;
    padding: 15px 32px;
    color: #fff;
    cursor: pointer;
    font-size: 16px;
    font-weight: 500;
    border-radius: 35px;
    transition: color .4s linear;
    position: absolute;
    top: 65px;
    right: 100px;
    text-decoration: none;
}

.wcard2 a {
    background: #ff1616;
    font-family: "Roboto", sans-serif;
    padding: 15px 32px;
    color: #fff;
    cursor: pointer;
    font-size: 16px;
    font-weight: 500;
    border-radius: 35px;
    transition: color .4s linear;
    position: absolute;
    top: 65px;
    right: 100px;
    text-decoration: none;
}

.join-form {
    background-image: url("../assets/newssettler.webp");
    margin-top: 20px;
    padding-bottom: 90px;
}

.join-form h1 {
    color: #fff;
    text-align: center;
    font-weight: 400;
    padding-top: 70px;
    margin-bottom: 20px;
}

.join-form p {
    font-family: "Roboto", sans-serif;
    text-align: center;
    color: #9498a7;
    font-size: 16px;
    line-height: 1.6;
    font-weight: 300;
}

.join-form form{
    margin-top: 20px;
    text-align: center;
}

input {

    border-radius: 50px;
    line-height: 2;
    height: 50px;
    padding: 15px 24px;
    color: #232f55;
    font-size: 16px;
    border-radius: 25px;
    background: #fff;
    border: 0;
}

button {
    height: 50px;
    border: 0;
    background: #ff1616;
    border-radius: 50px;
    padding: 15px 26px;
    color: #fff;
    margin-left: 5px;
    cursor: pointer;
    font-size: 16px;
    font-weight: 500;
}
</style>