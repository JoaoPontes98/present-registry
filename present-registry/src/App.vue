<template>
  <div id="app">
    <NavBar />
    <router-view></router-view> 
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  },
}
</script>

<style>
  * {
    margin:0;
    padding: 0;
    box-sizing: border-box;
  }

  main {
    width: 100vw;
    min-height: 100vh;
    overflow: hidden;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  body {
    background-image: url("./assets/images/PinkSky.jpg");
    background-repeat:no-repeat;
    background-position: center center;
    background-size: cover;
  }

  .hide {
    margin: 0;
    padding: 0;
    display: none;
  }
</style>
