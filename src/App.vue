<template>
  <div id="app">
    <TheHeader />
    <router-view/>
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from "./components/theHeader.vue";
import TheFooter from "./components/theFooter.vue";
  export default {
    components: {
      TheHeader,
      TheFooter
    }
  }
</script>


<style>
</style>
