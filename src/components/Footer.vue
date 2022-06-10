<template>
    <!-- Footer Start -->
    <div class="container-fluid text-white px-sm-3 px-md-5" id="header">
        <div class="row pt-5">
            <div class="col-lg-3 col-md-6 mb-5">
                <a href="" class="navbar-brand font-weight-bold text-primary m-0 mb-4 p-0" style="font-size: 40px; line-height: 40px;">
                    <img src="../assets/crop_logo.png" alt="" width="70" height="70"/>
                    <span class="text-white">Salted Caramel</span>
                </a>
                <p>The sweetest spot to earn passive income.</p>
                <div class="d-flex justify-content-start mt-4">
                    <a class="btn btn-outline-light rounded-circle text-center mr-2 px-0"
                        style="width: 38px; height: 38px;" href="#"><i class="fab fa-twitter"></i></a>
                    <a class="btn btn-outline-light rounded-circle text-center mr-2 px-0"
                        style="width: 38px; height: 38px;" href="#"><i class="fab fa-discord"></i></a>
                    <a class="btn btn-outline-light rounded-circle text-center mr-2 px-0"
                        style="width: 38px; height: 38px;" href="#"><i class="fab fa-github"></i></a>
                    <a class="btn btn-outline-light rounded-circle text-center mr-2 px-0"
                        style="width: 38px; height: 38px;" href="#"><i class="fab fa-telegram"></i></a>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 mb-5">
            </div>
            <div class="col-lg-3 col-md-6 mb-5">
                <h3 class="text-light mb-4">Products</h3>
                <div class="d-flex flex-column justify-content-start">
                  <router-link to="/soon" class="text-white mb-2"><i class="fa fa-angle-right mr-2"></i>Staking</router-link>
                  <router-link to="/soon" class="text-white mb-2"><i class="fa fa-angle-right mr-2"></i>Platform Sharing</router-link>
                  <router-link to="/soon" class="text-white mb-2"><i class="fa fa-angle-right mr-2"></i>Vote / DAO</router-link>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 mb-5">
                <h3 class="text-light mb-4">Support</h3>
                <div class="d-flex flex-column justify-content-start">
                    <router-link to="/soon" class="text-white mb-2"><i class="fa fa-angle-right mr-2"></i>FAQ</router-link>
                    <router-link to="/soon" class="text-white mb-2"><i class="fa fa-angle-right mr-2"></i>Step-by-Step Guide</router-link>
                    <a class="text-white mb-2" href="https://docs.saltedcaramel.xyz/"><i class="fa fa-angle-right mr-2"></i>Whitepaper</a>
                </div>
            </div>
        </div>
    </div>
    <!-- Footer End -->
</template>

<script>
export default {
  name: 'FooterVue',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#header {
    background: #888870;
    color: white;
}
</style>
