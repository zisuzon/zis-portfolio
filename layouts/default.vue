<template>
  <div id="wrapper">
    <nuxt/>
    <!-- Sidebar -->
    <side-bar></side-bar>

  </div>
</template>

<script>
import SideBar from '~/components/SideBar.vue'
export default {
  components: {
    SideBar
  }
}
</script>


<style src="~/assets/css/main.css">
</style>
