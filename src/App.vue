<template>
  <NavBarComp/>
  <router-view/>
  <Footer-comp/>
</template>

<script>

import FooterComp from './components/Footer-comp.vue'
import NavBarComp from './components/NavBar-comp.vue'


  export default {
  components: { FooterComp },
    component: {NavBarComp, FooterComp}
  }
</script>
<!-- <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style> -->
