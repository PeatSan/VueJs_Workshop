<template>
  <div id="app">
    <router-link to="/HelloWorld"> Home </router-link> |
    <router-link to="/Contact"> Contact </router-link> |
    <router-link to="/Project"> Project </router-link> 
    <router-view />
  </div>
</template>

<script>
export default {
   name: 'App',

   data: () => ({
      //
   })
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.router-link-exact-active {
  color: blue;
}
</style>