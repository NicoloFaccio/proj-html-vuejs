<script>
  import AppImage from '../components/Main/AppImage.vue';


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

    <section class="d-flex flex-column align-items-center"> 
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
      <div class="shop-products d-flex flex-column align-items-center my-5">
        <span class="fw-bolder tx-yellow text-capitalize mt-5">
          tranding online store
        </span>

        <h4 class="text-white text-uppercase">gogrin all <span class="tx-yellow">organic</span> food</h4>

        <span class="fw-bolder tx-yellow text-capitalize">
          tranding online store
        </span>

        <h4 class="text-white text-uppercase">gogrin all <span class="tx-yellow">organic</span> food</h4>

        <!-- LIST OF POSSIBLITIES -->
        <ul class="d-flex gap-2 my-4">
          <li>
            <a href="#" class="text-white text-capitalize text-decoration-none">
              all product
            </a>
          </li>

          <li>
            <a href="#" class="text-white text-capitalize text-decoration-none">
              apple
            </a>
          </li>

          <li>
            <a href="#" class="text-white text-capitalize text-decoration-none">
              food
            </a>
          </li>

          <li>
            <a href="#" class="text-white text-capitalize text-decoration-none">
              orange
            </a>
          </li>

          <li>
            <a href="#" class="text-white text-capitalize text-decoration-none">
              vegetable
            </a>
          </li>
        </ul>

        <!-- PRODUCTS AND PRICES -->
        <div class="container-fluid prices-products">
          <div class="row">
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure>
                <img src="../assets/img/s5.jpg" alt="shop fruits">
              </figure>

              <h6 class="text-white text-capitalize">
                fress Apple
              </h6>

              <span class="tx-yellow fw-bolder"> 
                &dollar;18 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure class="position-relative">
                <img src="../assets/img/s2.jpg" alt="shop fruits">

                <span class="span-sale bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>
              </figure>
              
              <h6 class="text-white text-capitalize">
                fress cobies
              </h6>

              <span class="tx-yellow fw-bolder"> 
                <span class="tx-yellow text-decoration-line-through opacity-75">&dollar;18</span> &dollar;17 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure>
                <img src="../assets/img/s8.jpg" alt="shop fruits">
              </figure>
              
              <h6 class="text-white text-capitalize">
                fresh watermelon 
              </h6>

              <span class="tx-yellow fw-bolder"> 
                &dollar;15
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure class="position-relative">
                <img src="../assets/img/s1.jpg" alt="shop fruits">

                <span class="span-sale bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>
              </figure>
              
              <h6 class="text-white text-capitalize">
                organic juice
              </h6>

              <span class="tx-yellow fw-bolder"> 
                <span class="tx-yellow text-decoration-line-through opacity-75">&dollar;20</span> &dollar;15 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure class="position-relative">
                <img src="../assets/img/s4.jpg" alt="shop fruits">

                <span class="span-sale bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>
              </figure>
              
              <h6 class="text-white text-capitalize">
                fresh blueberries 
              </h6>

              <span class="tx-yellow fw-bolder"> 
                <span class="tx-yellow text-decoration-line-through opacity-75">&dollar;19</span> &dollar;14 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure>
                <img src="../assets/img/s10.jpg" alt="shop fruits">
              </figure>
              
              <h6 class="text-white text-capitalize">
                organic letus 
              </h6>

              <span class="tx-yellow fw-bolder"> 
                &dollar;23
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure class="position-relative">
                <img src="../assets/img/s9.jpg" alt="shop fruits">

                <span class="span-sale bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>
              </figure>
              
              <h6 class="text-white text-capitalize">
                red gajor
              </h6>

              <span class="tx-yellow fw-bolder"> 
                <span class="tx-yellow text-decoration-line-through opacity-75">&dollar;29</span> &dollar;26 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure>
                <img src="../assets/img/s7.jpg" alt="shop fruits">
              </figure>
              
              <h6 class="text-white text-capitalize">
                naga pepper 
              </h6>

              <span class="tx-yellow fw-bolder"> 
                &dollar;21
              </span>
            </div>
          </div>
        </div>

        <button class="btn buttons bg-yellow text-white mb-5">Products</button>
      </div>

      <!-- PART OF THE TESTIMONY -->
      <div>
        <figure>
          <img src="" alt="grammar image">
        </figure>
      </div>

      <p>

      </p>

      <div>
        <figure>
          <img src="" alt="">
        </figure>
        
        <figure>
          <img src="" alt="">
        </figure>
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

      .prices-products {
        margin: 0 auto;
        width: 85%;

        .span-sale {
          position: absolute;
          right: 15px;
          top: 15px;
        }
      }
    }
  }
  
</style>