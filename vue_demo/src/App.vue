<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<router-view/>-->
    <hello-world msg="Vue props value"></hello-world>
  </div>
</template>

<script>
  import HelloWorld from "./components/HelloWorld";


export default {
  components: {HelloWorld},
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
