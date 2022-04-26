<template>
    <div class="col-lg-4 col-md-6 pb-1">
        <div class="d-flex bg-light shadow-sm border-top rounded mb-4" style="padding: 20px;">
            <div class="pl-3 pr-3 w-100">
                <div>
                    <img src="url1" height="40px" width="40px" id="logo"/>
                    <i class="fa fa-angle-right ml-2" id="fontcolor"></i>
                    <img class="ml-2" src="url2" height="40px" width="40px" id="logo"/>
                    <i class="fa fa-plus ml-2" id="fontcolor"></i>
                    <img class="ml-2" src="url3" height="40px" width="40px" id="logo"/>
                </div>
                <div class="mt-3">
                    <h4 class="">Auto {{ token1 }}</h4>
                    <p class="card-subtitle mb-2 text-muted">Stake {{ token1 }} <br/>Earn {{ token1 }} + {{ token2 }}</p>
                    <h5 class="m-0" id="iconcolor">APY : 104.12%</h5>
                    <a href="#" class="btn mt-2 py-2 px-5 btn-block" id="bgcolor">Approve {{ token1 }}</a>
                </div>
                <div class="mt-3">
                    <button class="btn mt-2 py-2 px-5 btn-block" data-toggle="collapse" data-target="#details1">Details<i class="fa fa-angle-down ml-2" id="fontcolor"></i></button>
                </div>
                <div class="mt-3" id="details1">
                    <h4 class="">Auto {{ token1 }}</h4>
                    <p class="card-subtitle mb-2 text-muted">Stake {{ token1 }} <br/>Earn {{ token1 }} + {{ token2 }}</p>
                    <h5 class="m-0" id="iconcolor">APY : 104.12%</h5>
                    <a href="#" class="btn mt-2 py-2 px-5 btn-block" id="bgcolor">Approve {{ token1 }}</a>
                </div>
            </div> 
        </div>
    </div>
</template>

<script>
export default {
  name: 'PoolVue',
  props: ['url1', 'url2', 'url3', 'token1', 'token2']
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
