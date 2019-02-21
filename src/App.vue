<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">ABOUT</router-link>
    </div>
    <transition name="router-anims" enter-active-class="animated wobble" leave-active-class="animated wobble">
      <router-view/>
    </transition>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style>
@import "https://cdn.jsdelivr.net/npm/animate.css@3.5.1";
body{
  background: rgb(233, 233, 233);
  font-family: 'Helvetica, Arial, sans-serif';
}
html, body{
  height: calc(100% - 50px);
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.page {
    position: fixed;
    width: inherit;
  } 
</style>