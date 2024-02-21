<script>
  export default {
    name: 'AppMenu',
    components: {
      
    },
    props: [
      'propsElement'
    ],
    data(){
      return{
        menuInformations: {
          home: {
            InfoHome: 'HOME-1',
            InfoHome: 'HOME-2',
            InfoHome: 'HOME-3',
            InfoHome: 'HOME-LANDING',
            InfoHome: 'HOME-VIDEO',
          },
          about: {
            InfoAbout: 'ABOUT US',
            InfoAbout: 'LOCATIONS AROUND THE WORLD',
            InfoAbout: 'WELCOME ON OUR WEB-SITE '
          },
          service: {
            infoService: 'CUSTOMER SERVICE'
          },
        }
      }
    }
  }
</script>

<template>
  <!-- MENU OF THE WEB SITE -->
  <ul class="nav nav-pills">
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">HOME</a>
      <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Action</a></li>
        <li><a class="dropdown-item" href="#">Another action</a></li>
        <li><a class="dropdown-item" href="#">Something else here</a></li>
        <li><hr class="dropdown-divider"></li>
        <li><a class="dropdown-item" href="#">Separated link</a></li>
      </ul>
    </li>
</ul>
</template>

<style scoped lang="scss">
  
</style>