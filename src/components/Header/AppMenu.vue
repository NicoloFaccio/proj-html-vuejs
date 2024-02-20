<script>
  export default {
    name: 'AppMenu',
    components: {
      
    },
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
    <div class="menu">
      <div class="btn-group">
        <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" data-bs-auto-close="outside" aria-expanded="false">
          Clickable inside
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Menu item</a></li>
          <li><a class="dropdown-item" href="#">Menu item</a></li>
          <li><a class="dropdown-item" href="#">Menu item</a></li>
        </ul>
      </div>
    </div>
</template>

<style scoped lang="scss">
  
</style>