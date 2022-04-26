<template>
  <div class="stake">
    <Stake/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Stake from '@/components/Stake.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'StakeView',
  components: {
    Stake,
    Footer
  }
}
</script>
