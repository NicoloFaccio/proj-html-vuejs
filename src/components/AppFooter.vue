<script>
  export default {
    name: 'AppFooter', 
    components: {
      
    },
    data(){
      return{}
    }
  }
</script>

<template>
  <footer>
    <section class="footer-section-1">
      <div>
        <figure>
          <img src="../assets/img/footer-logo.png" alt="logo footer">
        </figure>
        
        <p class="text-white">
          War should never be entered upon until every <br> agency of peace has failed not to be good 
        </p>

        <div>
          <div>
            <button type="button" class="btn bg-green mx-2" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Tooltip on top">
              <i class="text-white fa-brands fa-facebook-f"></i>
            </button>

            <button type="button" class="btn bg-green mx-2" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Tooltip on top">
              <i class="text-white fa-brands fa-google-plus-g"></i>
            </button>
  
            <button type="button" class="btn bg-green mx-2" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Tooltip on top">
              <i class="text-white fa-brands fa-x-twitter"></i>
            </button>
  
            <button type="button" class="btn bg-green mx-2" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Tooltip on top">
              <i class="text-white fa-brands fa-pinterest"></i>
            </button>
          </div>
          
        </div>
      </div>
    </section>
  </footer>
</template>

<style scoped lang="scss">
  .footer-section-1 {
    background-image: url('../assets/img/footer-bg.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    padding-top: 100px;

    > div {
      margin: 0 auto;
      width: 60%;

      padding-bottom: 30px;
    }
  }
</style>