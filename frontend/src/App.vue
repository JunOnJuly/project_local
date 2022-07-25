<template>
  <div>
    <nav-bar-comp></nav-bar-comp>

    <router-view/>

  </div>
</template>

<script>
import NavBarComp from './components/basecomp/NavBarComp.vue'

export default {
  components: {
    NavBarComp,
  }
}
</script>

<style scoped>

#test {
  height: 100%;
  width: 100%;
  background-color: azure; 
}
</style>