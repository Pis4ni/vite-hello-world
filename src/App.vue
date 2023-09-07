<script>
import AppTitle from "./components/AppTitle.vue";
export default {

  data() {
    return {
      message:'realizzato con un template vite/vue'
    }
  },
  components: {
    AppTitle,
    // AppJumbo
  }
  
}
</script>

<template>
  <AppTitle></AppTitle>
  <hr>
  <span>{{ message }}</span>
  <hr>
  <!-- <AppJumbo></AppJumbo> -->

  
</template>
<style>
 
</style>