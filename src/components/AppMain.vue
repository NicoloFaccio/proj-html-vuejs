<script>
  export default {
    name: 'AppMain', 
    components: {
      
    },
    data(){
      return{}
    }
  }
</script>

<template>
  <main>
    <section class="generalInformatons">
      <!-- <div>
        <span>
          gogrin oragnic food store
        </span>

        <h1>
          Eating naturally & oragnic is alaways healthy.
        </h1>

        <button>
          about us 
        </button> 

        <button>
          our history
        </button>
      </div> -->

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
              <h5>Second slide label</h5>
              <p>Some representative placeholder content for the second slide.</p>
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
  </main>
</template>

<style scoped lang="scss">
  // .generalInformatons {
  //   background-image: url('../assets/img/H3-slider3.jpg');
  //   background-position: center;
  //   background-repeat: no-repeat;
  //   background-size: cover;
  // }

  @use '../styles/partials/variables' as *;
  @use '../styles/partials/mixins' as *;
  @use '../styles/general.scss' as *;

  .carousel-caption {
    bottom: 50%;
    width: 100%;
    left: 0%;
  }
</style>