<template>
    <section class="pad">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-xl-5 col-lg-5 col-md-12">

                    <div class="section-tittle">
                        <h2>Latest Published items</h2>
                    </div>
                </div>
                <div class="nav-p">
                    <nav>
                        <div class="nav">
                            <button :class="{active:activeFilter == 'all'}" @click="toggle('all')"
                                href="#nav-one">All</button>
                            <button :class="{active:activeFilter == 'horror'}" @click="toggle('horror')"
                                href="#nav-two">Horror</button>
                            <button :class="{active:activeFilter == 'thriller'}" @click="toggle('thriller')"
                                href="#nav-three">Thriller</button>
                            <button :class="{active:activeFilter == 'science'}" @click="toggle('science')"
                                href="#nav-four">Science
                                Fiction</button>
                            <button :class="{active:activeFilter == 'history'}" @click="toggle('history')"
                                href="#nav-five">History</button>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="tab-content">

                <div class="tab-data" :class="{activepan:activeFilter == 'all'}">
                    <div class="card">
                        <img src="../assets/feature/dark_space.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/good_guy.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/iw.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/queen.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/very_nice.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/dragon.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-data" :class="{activepan:activeFilter == 'horror'}">
                    <div class="card">
                        <img src="../assets/queen.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/red_planet.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/very_nice.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/dark_space.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/good_guy.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/iw.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-data" :class="{activepan:activeFilter == 'thriller'}">
                    <div class="card">
                        <img src="../assets/feature/dark_space.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/good_guy.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/iw.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/queen.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/very_nice.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/red_planet.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-data" :class="{activepan:activeFilter == 'science'}">
                    <div class="card">
                        <img src="../assets/feature/good_guy.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/very_nice.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/dark_space.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/red_planet.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/iw.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/queen.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-data" :class="{activepan:activeFilter == 'history'}">
                    <div class="card">
                        <img src="../assets/dragon.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/good_guy.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/iw.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/queen.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/very_nice.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <img src="../assets/feature/dark_space.webp" alt="">
                        <div class="properties-caption">
                            <h3><a href="book-details.html">Moon Dance</a></h3>
                            <p>J. R Rain</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="review">
                                    <div class="rating">
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star checked"></i>
                                        <i class="fa fa-star-half-o"></i>
                                    </div>
                                    <p>(<span>120</span> Review)</p>
                                </div>
                                <div class="price">
                                    <span>$50</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="browse">
                <div class="browse-btn">
                    <a @click="scrollToTop">Browse more</a>
                </div>
            </div>

        </div>


    </section>
</template>

<style scoped>
@media (min-width: 1400px) {
    .container {
        max-width: 1350px;
    }
}

.section-tittle h2 {
    font-family: "Playfair Display", serif;
    font-size: 30px;
    font-weight: 700;
    line-height: 1.4;
    margin-bottom: 22px;
}

.pad {
    padding: 95px 0 100px 0;
}

.nav button {
    text-decoration: none;
    border: 1px solid #EEE1E0;
    border-radius: 50px;
    font-size: 16px;
    font-weight: 400;
    padding: 7px 24px;
    margin-right: 8px;
}

.active {
    background-color: #FF1616;
    color: #fff !important;
}

.tab-content {
    margin: 20px 0;
}

.tab-data {
    display: none;
    grid-template-columns: auto auto auto auto auto auto;
    gap: 25px;
    animation: fadein 1s;
}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}


.activepan {
    display: grid;
}

.checked {
    color: #ff5700;
}

.fa {
    letter-spacing: 5px;
    color: #ff5700;
}

.properties-caption h3 a {
    font-family: "Playfair Display", serif;
    font-size: 20px;
    font-weight: 700;
    color: #1a1a1a;
    text-decoration: none;
}

.properties-caption {
    padding: 14px 20px 2px 20px;
    transition: all .4s ease-out 0s;
    background-color: #fff;
}

.properties-caption h3 a:hover {
    color: red;
}

.properties-caption P {
    color: #9498a7;
    font-size: 14px;
    margin-bottom: 10px;
}

.properties-caption .price span {
    color: #ff1616;
    font-size: 22px;
    font-weight: 500;
    cursor: pointer;
}

.browse {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 60px;
}

.browse .browse-btn a {
    font-family: "Roboto", "sans-serif";
    border: 1px solid #FF1616;
    color: #FF1616;
    border-radius: 30px;
    text-decoration: none;
    padding: 18px 40px;
    font-size: 16px;
    font-weight: 500;
    cursor: pointer;
    transition: all 250ms ease;
}

.browse .browse-btn a:hover {
    background-color: #ff1616;
    color: #fff;
}
</style>

<script>
export default {
    data() {
        return {
            activeFilter: 'all'
        }
    },
    methods: {
        toggle: function (filter) {
            this.activeFilter = filter;
        },
        scrollToTop: function () {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    }
};
</script>