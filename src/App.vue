<template>
  <div class="container-fluid bg-light position-relative shadow">
      <nav class="navbar navbar-expand-lg bg-light navbar-light py-3 py-lg-0 px-0 px-lg-5">
          <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
              <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
              <router-link to="/" class="navbar-brand font-weight-bold text-secondary" style="font-size: 50px;">
                <img src="./assets/crop_logo.png" alt="" width="70" height="70"/>
                <!--<span class="text-primary">Salted Caramel</span>-->
              </router-link>
              <div class="navbar-nav font-weight-bold mx-auto py-0">
                  <router-link to="/soon" class="nav-item nav-link active">ICO</router-link>
                  <router-link to="/soon" class="nav-item nav-link active">Staking</router-link>
                  <router-link to="/soon" class="nav-item nav-link active">Buy $CRML</router-link>
                  <a href="https://saltedcaramel.gitbook.io/saltedcaramel.xyz/" class="nav-item nav-link">Whitepaper</a>
              </div>
          </div>
          <router-link to="/" class="btn px-4" id="importantbutton">Connect Wallet</router-link>
      </nav>
  </div>
  <router-view/>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#importantbutton {
    background: #712E1E;
    color: white;
}
#header {
    background: #E59A59;
    color: white;
}
</style>