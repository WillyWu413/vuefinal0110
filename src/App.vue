<template>
  <div id="app">
    
    <!-- <HelloWorld/> -->
    <router-view></router-view>
    
  </div>
</template>

<script>
import HelloWorld from './components/manager/HelloWorld'

export default {
  name: 'App',
};
</script>

<style lang="scss">
@import "./assets/all";
</style>
