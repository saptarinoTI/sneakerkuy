<template>
  <!-- Related Products Section End -->
  <div class="related-products spad">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-title my-5">
            <h2>Related Products</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-3 col-sm-6">
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
              <div class="product-price">
                $14.00
                <span>$35.00</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
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
                  <router-link to="/product">+ Quick View</router-link>
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
        </div>
        <div class="col-lg-3 col-sm-6">
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
        </div>
        <div class="col-lg-3 col-sm-6">
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
        </div>
      </div>
    </div>
  </div>
  <!-- Related Products Section End -->
</template>

<script>
export default {
  name: "RelatedSneakerKuy"
};
</script>