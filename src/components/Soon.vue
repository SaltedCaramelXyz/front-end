<template>
  <!-- Header Start -->
  <div class="container-fluid px-0 px-md-5" id="header">
      <div class="row align-items-center px-3">
          <div class="col-lg-6 text-center text-lg-left">
              <h4 class="text-white mb-4 mt-5 mt-lg-0">Coming soon...</h4>
              <p class="text-white mb-4">
                Check for updates on socials or learn more with our documentation.
              </p>
              <a href="https://docs.saltedcaramel.xyz/" class="btn btn-light mt-1 py-3 px-5">Learn More</a>
          </div>
          <div class="col-lg-6 text-center text-lg-right">
              <img class="img-fluid mt-5 mb-5" src="../assets/pot.png" alt="">
          </div>
      </div>
  </div>
  <!-- Header End -->

</template>

<script>
export default {
  name: 'SoonVue',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
