<template>
    <div class="container">
        <div class="main">
            <div class="search">
                <img src="../assets/logo.webp">
                <input type="search" placeholder="Search book by author or publisher">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search"
                    viewBox="0 0 16 16">
                    <path
                        d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                </svg>
            </div>
            <div class="navbar">
                <a href="#">FAQ</a>
                <a href="#">Track Order</a>
                <a href="#"><img src="../assets/cart.svg"></a>
                <button class="main-btn">Sign in</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url(https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800;900&family=Roboto:wght@300;400;500;700;900&display=swap);

@media (min-width: 1400px) {
    .container {
        max-width: 1320px;
    }
}

.main {
    display: flex;
    justify-content: space-between;
    margin: 12px 0 12px 0;
    position: relative;
}

.main .search {
    display: flex;
    align-items: center;
}

.search input {
    margin-left: 40px;
    padding: 12px;
    width: 500px;
    border: 1px solid rgb(205, 193, 193);
    border-radius: 50px;
}

input:focus {
    outline: none !important;
    border-color: #719ECE;
    box-shadow: 0 0 5px #719ECE;
}

.main .search svg {
    position: relative;
    left: -45px;
    width: auto;
    height: 22px;
    color: red;
    cursor: pointer;
}

.navbar {
    padding-right: 0;
}

.navbar a {
    right: 0;
    color: #454e6d;
    padding: 0 20px;
    font-size: 16px;
}

.navbar .main-btn {
    font-size: 16px;
    border: none;
    padding: 12px 32px;
    border-radius: 50px;
    background-color: red;
    color: white;
    font-weight: 500;
}
</style>