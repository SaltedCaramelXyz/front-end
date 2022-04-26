<template>
  <!-- Header Start -->
  <div class="container-fluid px-0 px-md-5" id="header">
      <div class="row align-items-center px-3">
          <div class="col-lg-6 text-center text-lg-left">
              <h4 class="text-white mb-4 mt-5 mt-lg-0">Salted Caramel</h4>
              <h1 class="display-3 font-weight-bold text-white">The sweetest spot to earn passive income</h1>
              <p class="text-white mb-4">
                Stake your favorite crypto, Salted Caramel autocompounds it and rewards you with $CRML.<br/>
                Each token deposited register you for the big draw. Take your chance to get thousand of cryptos !<br/>
                Lock your $CRML and get even more passive income in $USDT.
              </p>
              <router-link to="/soon" class="btn mt-1 py-3 px-5" id="importantbutton">Stake Now !</router-link>
              <a href="" class="btn btn-light ml-3 mt-1 py-3 px-5">Learn More</a>
          </div>
          <div class="col-lg-6 text-center text-lg-right">
              <img class="img-fluid mt-5 mb-5" src="../assets/pot.png" alt="">
          </div>
      </div>
  </div>
  <!-- Header End -->

  <!-- Facilities Start -->
    <div class="container-fluid pt-5" id="homelist">
        <div class="container pb-3">
            <div class="row">
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-002-bricks h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Stake</h4>
                            <p class="m-0">Salted Caramel offers a large variety of staking pools with juicy APYs.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-041-abacus h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Earn Passive Income</h4>
                            <p class="m-0">Your crypto is automaticaly autocompounded with the same token you staked.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-021-juice-box h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Get Extra Tokens</h4>
                            <p class="m-0">Each staking pool below a certain value is boosted with $CRML rewards.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-040-puzzle h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Cumulate Tickets</h4>
                            <p class="m-0">We chose to reward loyalty more than huge portfolios. Stay long, Earn big.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-031-bell h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Big Draw</h4>
                            <p class="m-0">Every 7 days, Big Draw occurs and rewards winners with varierty of tokens.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 30px;">
                        <i class="flaticon-011-mat h1 font-weight-normal mb-3" id="iconcolor"></i>
                        <div class="pl-4">
                            <h4>Share Protocol Revenue</h4>
                            <p class="m-0">Lock your $CRML and get rewarded in $USDT.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Facilities Start -->
</template>

<script>
export default {
  name: 'HomeVue',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#homelist {
    background: #FFD5AF;
    color: black;
}

#iconcolor {
    color: #712E1E;
}
</style>
