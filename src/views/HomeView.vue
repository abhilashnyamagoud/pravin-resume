<template>
  <div class="home">
    <Navbar/>
    <Details/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar/Navbar.vue'
import Details from '../components/Details/Details.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar,
    Details
  }
}
</script>

<style lang='css' scoped>
.home{
   background: rgba(0, 0, 0, 0.76);
        color: white;
}
</style>
