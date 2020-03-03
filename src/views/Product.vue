<template>
  <div class="product">
    <HeaderSneakerKuy />

    <div>
      <!-- Breadcrumb Section Begin -->
      <div class="breacrumb-section text-left">
        <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <div class="breadcrumb-text product-more">
                <router-link to="/">
                  <i class="fa fa-home"></i> Home
                </router-link>
                <span>Detail</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Breadcrumb Section Begin -->

      <!-- Product Shop Section Begin -->
      <section class="product-shop spad page-details">
        <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <div class="row">
                <div class="col-lg-6">
                  <div class="product-pic-zoom">
                    <img class="product-big-img" :src="gambar_product" />
                  </div>
                  <div class="product-thumbs">
                    <carousel
                      class="product-thumbs-track ps-slider"
                      :items="3"
                      :dots="false"
                      :nav="false"
                    >
                      <div
                        class="pt"
                        @click="changeImage(thumbs[0])"
                        :class="thumbs[0] == gambar_product ? 'active' : ' ' "
                      >
                        <img src="img/products/product-1.jpg" alt />
                      </div>

                      <div
                        class="pt"
                        @click="changeImage(thumbs[1])"
                        :class="thumbs[1] == gambar_product ? 'active' : ' ' "
                      >
                        <img src="img/products/product-1.1.jpg" alt />
                      </div>

                      <div
                        class="pt"
                        @click="changeImage(thumbs[2])"
                        :class="thumbs[2] == gambar_product ? 'active' : ' ' "
                      >
                        <img src="img/products/product-1.2.jpg" alt />
                      </div>

                      <div
                        class="pt"
                        @click="changeImage(thumbs[3])"
                        :class="thumbs[3] == gambar_product ? 'active' : ' ' "
                      >
                        <img src="img/products/product-1.3.jpg" alt />
                      </div>
                    </carousel>
                  </div>
                </div>
                <div class="col-lg-6">
                  <div class="product-details text-left">
                    <div class="pd-title">
                      <span>shoes</span>
                      <h3>Product 1</h3>
                    </div>
                    <br />
                    <div class="pd-desc">
                      <span>description</span>
                      <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, error
                        officia. Rem aperiam laborum voluptatum vel, pariatur modi hic provident eum
                        iure natus quos non a sequi, id accusantium! Autem.
                      </p>
                      <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quam possimus quisquam
                        animi, commodi, nihil voluptate nostrum neque architecto illo officiis
                        doloremque et corrupti cupiditate voluptatibus error illum. Commodi expedita
                        animi nulla aspernatur.
                        Id asperiores blanditiis, omnis repudiandae iste inventore cum, quam sint
                        molestiae accusamus voluptates ex tempora illum sit perspiciatis. Nostrum dolor
                        tenetur amet, illo natus magni veniam quia sit nihil dolores.
                        Commodi ratione distinctio harum voluptatum velit facilis voluptas animi non
                        laudantium, id dolorem atque perferendis enim ducimus? A exercitationem
                        recusandae aliquam quod. Itaque inventore obcaecati, unde quam
                        impedit praesentium veritatis quis beatae ea atque perferendis voluptates velit
                        architecto?
                      </p>
                      <br />
                      <span>Price</span>
                      <h4>$495.00</h4>
                    </div>
                    <div class="quantity">
                      <router-link to="/cart" class="primary-btn pd-cart">Add To Cart</router-link>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Product Shop Section End -->
    </div>

    <RelatedSneakerKuy />

    <FooterSneakerKuy />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSneakerKuy from "@/components/HeaderSneakerKuy.vue";
import RelatedSneakerKuy from "@/components/RelatedSneakerKuy.vue";
import FooterSneakerKuy from "@/components/FooterSneakerKuy.vue";

import carousel from "vue-owl-carousel";

export default {
  name: "Product",
  components: {
    HeaderSneakerKuy,
    RelatedSneakerKuy,
    FooterSneakerKuy,
    carousel
  },

  data() {
    return {
      gambar_product: "img/products/product-1.jpg",
      thumbs: [
        "img/products/product-1.jpg",
        "img/products/product-1.1.jpg",
        "img/products/product-1.2.jpg",
        "img/products/product-1.3.jpg"
      ]
    };
  },
  methods: {
    changeImage(urlImage) {
      this.gambar_product = urlImage;
    }
  }
};
</script>

<style scoped>
.product-thumbs .pt {
  margin-right: 10px;
}
</style>