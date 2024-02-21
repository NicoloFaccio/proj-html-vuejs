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
                fresh apple
              </h6>

              <span class="tx-yellow fw-bolder"> 
                &dollar;18 
              </span>
            </div>
            <div class="col-3 mb-3 d-flex flex-column align-items-center">
              <figure class="position-relative">
                <img src="../assets/img/s2.jpg" alt="shop fruits">

                <span class="span-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>
              </figure>
              
              <h6 class="text-white text-capitalize">
                fresh cobies
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

                <span class="span-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
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

                <span class="span-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
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

                <span class="span-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
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
      <div class="d-flex flex-column align-items-center">
        <div>
          <i class="tx-green fa-solid fa-quote-left"></i>
        </div>
        
  
        <p class="text-center fw-bold">
          "Dessert pudding dessert jelly beans cupcake sweet caramels gingerbread. Fruitcake biscuit cheesecake. <br> Cookie topping sweets muffine pudding tart bear claw sugar plum croissant". We started as a small legal <br> consultancy. We have proved our competence and had many satisfied clients. <br> <br>
  
          <span class="text-capitalize fw-bolder">
            martha alex <br>
            <span class="text-capitalize fw-bolder tx-yellow">manager</span>          
          </span>
        </p>
  
        <div class="d-flex gap-3">
          <figure class="position-relative">
            <img src="../assets/img/offer-img01.jpg" alt="offer's image">

            <h3 class="title-position text-white">
              Fresh gurden tomato <br> combo offer...&dollar;37
            </h3>

            <span class="tags-position">
              <a class="text-uppercase text-white fw-bold" href="#">shop now</a>
            </span>
          </figure>
  
          <figure class="position-relative">
            <img src="../assets/img/offer-img02.jpg" alt="offer's image">

            <h3 class="title-position text-white">
              Some organic healthy fruits <br> combo offer...&dollar;49
            </h3>

            <span class="tags-position">
              <a class="text-uppercase text-white fw-bold" href="#">shop now</a>
            </span>
          </figure>
        </div>
      </div>

      <!-- PART OF THE NUMBERS -->
      <div class="bg-numbers d-flex justify-content-center">
        <div class="single-number d-flex flex-column align-items-center p-2">
          <span class="tx-yellow fs-1 fw-bold">29+</span>
          <span class="text-white fw-bolder">Years of Expenrienced</span>
        </div>

        <div class="single-number d-flex flex-column align-items-center p-2">
          <span class="tx-yellow fs-1 fw-bold">200+</span>
          <span class="text-white fw-bolder text-capitalize">everyday online delivery</span>
        </div>

        <div class="single-number d-flex flex-column align-items-center p-2">
          <span class="tx-yellow fs-1 fw-bold">20K</span>
          <span class="text-white fw-bolder text-capitalize">client satysfaction</span>
        </div>

        <div class="d-flex flex-column align-items-center p-2">
          <span class="tx-yellow fs-1 fw-bold">30+</span>
          <span class="text-white fw-bolder text-capitalize">award winning</span>
        </div>
      </div>

      <!-- PART OF THE SALES AND THE APPOIMENT -->
      <div>
        <div>
          <div class="bg-title my-4 text-center">
            <span class="tx-yellow fw-bold">Running week top seling</span>
            <h3 class="text-uppercase tx-green">top <span class="tx-yellow">trending</span> organic food</h3>
          </div>

          <div class="d-flex justify-content-center gap-3">
            <div class="card" style="width: 18rem;">
              <figure class="text-center">
                <img src="../assets/img/s5.jpg" class="card-img-top" alt="fruits images">

                <h6 class="fw-bold text-capitalize">
                  fress Apple
                </h6>

                <span> 
                  &dollar;18 
                </span>
              </figure>
            </div>

            <div class="card" style="width: 18rem;">
              <figure class="text-center position-relative">
                <img src="../assets/img/s2.jpg" class="card-img-top" alt="fruits images">

                <span class="fruit-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>

                <h6 class="fw-bold text-capitalize">
                  fresh cobies
                </h6>


                <span class="text-decoration-line-through pe-1">
                  &dollar;18
                </span>
                <span class="text-decoration-underline"> 
                  &dollar;17
                </span>
              </figure>
            </div>

            <div class="card" style="width: 18rem;">
              <figure class="text-center">
                <img src="../assets/img/s8.jpg" class="card-img-top" alt="fruits images">

                <h6 class="fw-bold text-capitalize">
                  fresh watermelon
                </h6>

                <span> 
                  &dollar;15
                </span>
              </figure>
            </div>

            <div class="card" style="width: 18rem;">
              <figure class="text-center position-relative">
                <img src="../assets/img/s1.jpg" class="card-img-top" alt="fruits images">

                <span class="fruit-sale position-absolute bg-yellow text-white fw-bolder py-1 px-2">
                  sale!
                </span>

                <h6 class="fw-bold text-capitalize">
                  fresh cobies
                </h6>


                <span class="text-decoration-line-through pe-1">
                  &dollar;20
                </span>
                <span class="text-decoration-underline"> 
                  &dollar;15
                </span>
              </figure>
            </div>
          </div>
        </div>

        <div class="my-5 text-center bg-image py-5">
          <p class="text-white text-uppercase fw-bold">here you can get 100% tresh organic food</p>
          <h3 class="text-white">Best organic food up to 25% off for all product</h3>
          <p class="text-white px-3">The most beatiful people we have known defeat, known suffering, known struggle, known loss, and have found their way out of those depths. The most beatiful people we have known are those who have known defeat, known suffering</p>
          <div>
            <button class="btn bg-yellow text-white me-3">
              <i class="fa-solid fa-comment"></i> +088123 65 906
            </button>

            <button class="btn bg-green text-white fw-bold">
              apoinment
            </button>
          </div>
        </div>

      </div>

      <!-- PART OF THE BLOG AND LOGOS -->
      <div>
        <div class="bg-title my-4 text-center">
          <span class="tx-yellow fw-bold">The news what we have</span>
          <h3 class="text-uppercase tx-green">gogrin latest <span class="tx-yellow">news</span> feed</h3>
        </div>

        <div class="d-flex gap-3 justify-content-center">
          <div class="card" style="width: 18rem;">
            <img src="../assets/img/blo1-300x300.jpg" class="card-img-top image-blog" alt="blog's images">
            <div class="card-body">
              <div class="mb-2">
                <span>
                  <i class="fa-solid fa-user tx-yellow"></i> Gogrin
                </span>
                <span>
                  <i class="fa-regular fa-clock tx-yellow"></i> 17 Dec 2022
                </span>
              </div>
              <h5 class="card-title tx-green">Where I live, I am surrounded by fresh, organic food, so I eat very well.</h5>
              <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat, possimus dolorem delectus accusantium voluptate consequatur explicabo.</p>
              <a href="#" class="tx-green text-uppercase fw-bold">read more...</a>
            </div>
          </div>

          <div class="card" style="width: 18rem;">
            <img src="../assets/img/blo2-300x300.jpg" class="card-img-top" alt="blog's images">
            <div class="card-body">
              <div class="mb-2">
                <span>
                  <i class="fa-solid fa-user tx-yellow"></i> Gogrin
                </span>
                <span>
                  <i class="fa-regular fa-clock tx-yellow"></i> 16 Dec 2022
                </span>
              </div>
              <h5 class="card-title tx-green">What we get at home is 100% organic food. We are also 90% vegetarian.</h5>
              <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat, possimus dolorem delectus accusantium voluptate consequatur explicabo.</p>
              <a href="#" class="tx-green text-uppercase fw-bold">read more...</a>
            </div>
          </div>

          <div class="card" style="width: 18rem;">
            <img src="../assets/img/blo3-300x300.jpg" class="card-img-top" alt="blog's images">
            <div class="card-body">
              <div class="mb-2">
                <span>
                  <i class="fa-solid fa-user tx-yellow"></i> Gogrin
                </span>
                <span>
                  <i class="fa-regular fa-clock tx-yellow"></i> 15 Dec 2022
                </span>
              </div>
              <h5 class="card-title tx-green">If we as society are willing to have a preference for organic food farmer</h5>
              <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat, possimus dolorem delectus accusantium voluptate consequatur explicabo.</p>
              <a href="#" class="tx-green text-uppercase fw-bold">read more...</a>
            </div>
          </div>
        </div>

        <div>
          <figure>
            <img src="" alt="Logos">
          </figure>
        </div>
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
          right: 15px;
          top: 15px;
        }
      }
    }

    .fa-quote-left {
      font-size: 60px;
    }

    .title-position {
      position: absolute;
      top: 10px;
      left: 30px;
    }

    .tags-position {
      position: absolute;
      left: 30px;
      bottom: 10px;
    }

    .bg-numbers {
      background-image: url('../assets/img/milesim-bg.jpg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
      width: 100%;

      .single-number {
        border-right: 3px solid $Yellow;
      }
    }

    .bg-title {
      background-image: url('../assets/img/title-shap.png');
      background-repeat: no-repeat;
      background-position: center;
      background-size: contain;
    }

    .fruit-sale {
      top: 20px;
      right: 20px;
    }
    .bg-image {
      background-image: url('../assets/img/call-to-bg.jpg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
    }

    .image-blog {
     
    }
  }
</style>