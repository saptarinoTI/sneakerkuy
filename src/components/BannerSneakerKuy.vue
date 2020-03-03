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
                  <img src="img/products/product-1.jpg" alt />
                  <ul>
                    <li class="w-icon active">
                      <router-link to="/product">
                        <i class="icon_bag_alt"></i>
                      </router-link>
                    </li>
                    <li class="quick-view">
                      <router-link to="/product">+ Quick View</router-link>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Shoes</div>
                  <router-link to="/product">
                    <h5>Product 1</h5>
                  </router-link>
                  <div class="product-price">
                    $14.00
                    <span>$35.00</span>
                  </div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/product-2.jpg" alt />
                  <ul>
                    <li class="w-icon active">
                      <a href="#">
                        <i class="icon_bag_alt"></i>
                      </a>
                    </li>
                    <li class="quick-view">
                      <a href="#">+ Quick View</a>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Shoes</div>
                  <a href="#">
                    <h5>Product 2</h5>
                  </a>
                  <div class="product-price">$13.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/product-3.jpg" alt />
                  <ul>
                    <li class="w-icon active">
                      <a href="#">
                        <i class="icon_bag_alt"></i>
                      </a>
                    </li>
                    <li class="quick-view">
                      <a href="#">+ Quick View</a>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Shoes</div>
                  <a href="#">
                    <h5>Product 3</h5>
                  </a>
                  <div class="product-price">$34.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/product-4.jpg" alt />
                  <ul>
                    <li class="w-icon active">
                      <a href="#">
                        <i class="icon_bag_alt"></i>
                      </a>
                    </li>
                    <li class="quick-view">
                      <a href="#">+ Quick View</a>
                      <!-- </li>
                    <li class="w-icon">
                      <a href="#">
                        <i class="fa fa-random"></i>
                      </a>
                      </li>-->
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Shoes</div>
                  <a href="#">
                    <h5>Product 4</h5>
                  </a>
                  <div class="product-price">$34.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/products/product-5.jpg" alt />
                  <ul>
                    <li class="w-icon active">
                      <a href="#">
                        <i class="icon_bag_alt"></i>
                      </a>
                    </li>
                    <li class="quick-view">
                      <a href="#">+ Quick View</a>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Shoes</div>
                  <a href="#">
                    <h5>Product 5</h5>
                  </a>
                  <div class="product-price">$34.00</div>
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
import carousel from "vue-owl-carousel";

export default {
  name: "BannerSneakerKuy",
  components: {
    carousel
  }
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
</style>