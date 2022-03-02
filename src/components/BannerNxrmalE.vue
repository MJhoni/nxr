<template>
    <div>
            <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <carousel class="product-slider" :items="3" :dots="false" :nav="false" :autoplay="true">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/products/aespa 1.jfif" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view">
                                        <router-link to="/product">+ Quick View
                                        </router-link>
                                        </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">T-Shirt</div>
                                <router-link to="/product">
                                    <h5>Aespa-Next Level</h5>
                                </router-link>
                                <div class="product-price">
                                    $14.00
                                    <span>$35.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/products/butter 4.jfif" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product2.html">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Sweater</div>
                                <a href="#">
                                    <h5>BTS-Butter</h5>
                                </a>
                                <div class="product-price">
                                    $13.00
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/products/buaya 5.jfif" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product3.html">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">T-Shirt</div>
                                <a href="#">
                                    <h5>Buaya Darat</h5>
                                </a>
                                <div class="product-price">
                                    $34.00
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/products/lisa 1.jfif" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">T-Shirt</div>
                                <a href="#">
                                    <h5>Lalisa Manoban</h5>
                                </a>
                                <div class="product-price">
                                    $34.00
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/products/badut 3.jfif" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">T-Shirt</div>
                                <a href="#">
                                    <h5>Harley Queen</h5>
                                </a>
                                <div class="product-price">
                                    $34.00
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->
    </div>
</template>

<script>

import carousel from 'vue-owl-carousel'

export default {
    name: 'BannerNxrmalE',
    components: {
        carousel
    }
  }
</script>

<style scoped>
.product-item{
    margin-right: 25px;
}
</style>