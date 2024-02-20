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
    <section>
      <div class="d-flex align-items-center gap-2 mt-3">
        <figure>
          <img src="../../src/assets/img/logo.png" alt="Logo Gogrin">
        </figure>

        <!-- MENU OF THE WEB SITE -->
        <div>
          <AppMenu/>
        </div>
      </div>

      <ul>
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </section>
  </header>
</template>

<style scoped lang="scss">
  header {
    section:first-child {
      background-color: rgba(0, 113, 103, 1);
      color: white;
      height: 50px;

      div{
        margin: 0 auto;
        width: 90%;
  
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
      margin: 0 auto;
      width: 90%;
    }
  }
</style>