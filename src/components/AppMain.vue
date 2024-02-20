<script>
//  import AppImage from './Main/AppImage.vue';

  export default {
    name: 'AppMain', 
    components: {
      AppImage
    },
    data(){
      return{}
    }
  }
</script>

<template>
  <main>
    <section class="generalInformatons">
      <!-- PART ABOUT THE CAROUSEL -->
      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/img/H3-slider3.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <span class="text-uppercase fw-bolder">
                gogrin oragnic food store
              </span>

              <h1 class="fs-1">
                Eating naturally & oragnic is alaways healthy.
              </h1>
      
              <button class="btn bg-yellow buttons me-3">
                about us 
              </button> 
      
              <button class="btn bg-green buttons">
                our history
              </button>
            </div>
          </div>

          <div class="carousel-item">
            <img src="../assets/img/slider.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5 class="fs-1">All our products are eco-friendly</h5>
              <p class="text-uppercase fw-bolder">All our products have been grown ecologically and organically using the latest technology.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </section>

    <section>
      <!-- PART OF THE TEXT -->
      <div class="d-flex mt-5">
        <h3 class="tx-green">
          <span class="tx-yellow">Look what</span> consure power <br> has done with <span class="tx-yellow">oraganic food;</span> we <br> can do the same with clothes. 
        </h3>
        <p>
          I have a need to make these sorts of connections literal sometimes, and a vehicle often helps to do that. <br>
          I have relantionship to hosting culture. <span class="tx-yellow">It isn't really about it helps to do that. I have relantionship to hosting culture.</span>
          <br> 
          <br>
          Need to make these sorts of connections literal sometimes, and a vehicle often helps to do that. I have relantionship to hosting culture.
        </p>
        <figure>
          <img src="../assets/img/fe-shap1-1.png" alt="">
        </figure>
      </div>

      <!-- PART OF THE PRODUCTS -->
      <div class="shop-products d-flex flex-column align-items-center">
        <span class="fw-bolder tx-yellow text-capitalize mt-5">
          tranding online store
        </span>

        <h4 class="text-white text-uppercase">gogrin all <span class="tx-yellow">organic</span> food</h4>

        <span class="fw-bolder tx-yellow text-capitalize">
          tranding online store
        </span>

        <h4 class="text-white text-uppercase">gogrin all <span class="tx-yellow">organic</span> food</h4>

        <div class="container-fluid">

        </div>

        <button class="btn buttons bg-yellow text-white">Products</button>
      </div>
    </section>
  </main>
</template>

<style scoped lang="scss">
  @use '../styles/partials/variables' as *;
  @use '../styles/partials/mixins' as *;
  @use '../styles/general.scss' as *;

  section:last-child {
    @include GeneralWidth;

    .carousel-caption {
      bottom: 50%;
      width: 100%;
      left: 0%;
    }

    .shop-products {
      background-image: url('../assets/img/shop-bg-img.jpg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
    }
  }
  
</style>