<template>
  <!-- Facilities Start -->
    <div class="container-fluid pt-5" id="homelist">
        <div class="container pb-3">
            <div class="row" id="pools">
                <!--<Pool 
                    url1="../assets/icons/bsw.svg" 
                    url2="../assets/icons/bsw.svg" 
                    url3="../assets/icons/bsw.svg" 
                    token1="BSW"
                    token2="CRML"
                />-->
                <div class="col-lg-4 col-md-6 pb-1" id="pool">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 20px;">
                        <div class="pl-3 pr-3 w-100">
                            <div>
                                <img src="../assets/icons/bsw.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-angle-right ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/icons/bsw.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-plus ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/token.png" height="40px" width="40px" id="logo"/>
                            </div>
                            <div class="mt-3">
                                <h4 class="">Auto BSW</h4>
                                <p class="card-subtitle mb-2 text-muted">Stake BSW <br/>Earn BSW + CRML</p>
                                <h5 class="m-0" id="iconcolor">APY : 104.12%</h5>
                                <a href="#" class="btn mt-2 py-2 px-5 btn-block" id="bgcolor">Approve BSW</a>
                            </div>
                            <div class="mt-3">
                                <button class="btn mt-2 py-2 px-5 btn-block" data-toggle="collapse" data-target="#details1" aria-expanded="false" aria-controls="details1">Details<i class="fa fa-angle-down ml-2" id="fontcolor"></i></button>
                            </div>
                            <div class="mt-3 collapse text-left" id="details1">
                                <p class="card-subtitle mb-2">Total Staked : 1.000.000 BSW</p>
                                <p class="card-subtitle mb-2">Unstaking fee : 0.1% within 72h</p>
                                <div class="text-right">
                                    <a href="#" class="card-subtitle mb-2 text-right">Token Info<i class="fa fa-link ml-2"></i></a><br/>
                                    <a href="#" class="card-subtitle mb-2 text-right">Project Site<i class="fa fa-link ml-2"></i></a><br/>
                                    <a href="#" class="card-subtitle mb-2 text-right">View Contract<i class="fa fa-link ml-2"></i></a>
                                </div>
                            </div>
                        </div> 
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1" id="pool">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 20px;">
                        <div class="pl-3 pr-3 w-100">
                            <div>
                                <img src="../assets/icons/pcs.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-angle-right ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/icons/pcs.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-plus ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/token.png" height="40px" width="40px" id="logo"/>
                            </div>
                            <div class="mt-3">
                                <h4 class="">Auto CAKE</h4>
                                <p class="card-subtitle mb-2 text-muted">Stake CAKE <br/>Earn CAKE + CRML</p>
                                <h5 class="m-0" id="iconcolor">APY : 109.01%</h5>
                                <a href="#" class="btn mt-2 py-2 px-5 btn-block" id="bgcolor">Approve CAKE</a>
                            </div>
                            <div class="mt-3">
                                <a href="#" class="btn mt-2 py-2 px-5 btn-block" >Details<i class="fa fa-angle-down ml-2" id="fontcolor"></i></a>
                            </div>
                        </div> 
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 pb-1" id="pool">
                    <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 20px;">
                        <div class="pl-3 pr-3 w-100">
                            <div>
                                <img src="../assets/icons/banana.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-angle-right ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/icons/banana.svg" height="40px" width="40px" id="logo"/>
                                <i class="fa fa-plus ml-2" id="fontcolor"></i>
                                <img class="ml-2" src="../assets/token.png" height="40px" width="40px" id="logo"/>
                            </div>
                            <div class="mt-3">
                                <h4 class="">Auto BANANA</h4>
                                <p class="card-subtitle mb-2 text-muted">Stake BANANA <br/>Earn BANANA + CRML</p>
                                <h5 class="m-0" id="iconcolor">APY : 92.83%</h5>
                                <a href="#" class="btn mt-2 py-2 px-5 btn-block" id="bgcolor">Approve BANANA</a>
                            </div>
                            <div class="mt-3">
                                <a href="#" class="btn mt-2 py-2 px-5 btn-block" >Details<i class="fa fa-angle-down ml-2" id="fontcolor"></i></a>
                            </div>
                        </div> 
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Facilities Start -->
</template>

<script>
//import Pool from '@/components/Pool.vue'

export default {
  name: 'HomeVue',
  //components: {
    //Pool
  //},
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

#fontcolor {
    color: #712E1E;
}
#bgcolor {
    background: #712E1E;
    color:white
}
</style>
