<template>
  <div id="app">
    <NavBar>

    </NavBar>
    <router-view/>
  </div>
</template>

<script>
import NavBar from '@/components/NavigationBar.vue' 

export default {
  components : {
    NavBar
  }
}
</script>




<style>
</style>


