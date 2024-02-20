<script>
  import AppMenu from '../components/Header/AppMenu.vue';

  export default {
    name: 'AppHeader',
    components: {
      AppMenu
    },
    data(){
      return{}
    }
  }
</script>

<template>
  <header>
    <!-- PART OF THE HEADER WITH THE ICONS FOR THE SOCIAL MEDIA -->
    <section>
      <div class="d-flex justify-content-between align-items-center">
        <ul class="d-flex gap-4 py-2">
          <li>
            <a href="#">
              <i class="fa-solid fa-location-dot"></i> North Baukhula, tala, USA 
            </a>
          </li>

          <li>
            <a href="#">
              <i class="fa-solid fa-envelope"></i> demo@example.com
            </a>
          </li>
        </ul>

        <!-- ICONS FOR THE SOCIAL MEDIA -->
        <ul class="d-flex gap-3">
          <li class="pe-4">
            <i class="fa-regular fa-clock"></i> 8:30AM - 8:30PM
          </li>

          <li>
            <a href="#">
              <i class="fa-brands fa-facebook-f"></i>
            </a>
          </li>

          <li>
            <a href="#">
              <i class="fa-brands fa-x-twitter"></i>
            </a>
          </li>

          <li>
            <a href="#">
              <i class="fa-brands fa-instagram"></i>
            </a>
          </li>

          <li>
            <a href="#"><i class="fa-brands fa-pinterest"></i></a>
          </li>
        </ul>
      </div>
    </section>
    
    <!-- PART OF THE MENU AN ORDINATION -->
    <section class="d-flex justify-content-between align-items-center">
      <div class="d-flex align-items-center gap-2 mt-3">
        <figure>
          <img src="../../src/assets/img/logo.png" alt="Logo Gogrin">
        </figure>

        <!-- MENU OF THE WEB SITE -->
        <div>
          <AppMenu/>
        </div>
      </div>

      <ul class="d-flex gap-3 align-items-center">
        <li>
          <i class="bg-yellow text-white rounded-circle p-2 fa-solid fa-magnifying-glass"></i>
        </li>

        <li>
          <i class="fa-solid fa-cart-shopping"></i>
          <!-- <span>0</span> -->
        </li>

        <li>
          <span class="btn bg-yellow buttons">order now</span>
        </li>
      </ul>
    </section>
  </header>
</template>

<style scoped lang="scss">
  @use '../styles/partials/variables' as *;
  @use '../styles/partials/mixins' as *;
  @use '../styles/general.scss' as *;
  
  header {
    section:first-child {
      background-color: $Green;
      color: white;
      height: 50px;

      div{
        @include GeneralWidth;
  
        ul {
          padding-left: 0px;

          li {
            a {
              color: white;
            }
          }
        } 
      }
    }

    section:last-child {
      @include GeneralWidth;

      ul {
        li:nth-child(2) {
          position: relative;
          .fa-cart-shopping {
            color: $Green;
          }

          // span {
          //   position: absolute;
          //   top: -10px;

          //   background-color: $Yellow;
          //   color: white;

          //   border-radius: 50%;
          //   width: 20px;
          //   aspect-ratio: 1;
          // }
        }
      }
    }
  }
</style>