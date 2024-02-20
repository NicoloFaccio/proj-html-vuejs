<script>
  export default {
    name: 'AppMenu',
    components: {
      
    },
    data(){
      return{}
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