<template>
  <div id="app">
    <NavBar/>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

import '../node_modules/materialize-css/dist/css/materialize.min.css';
import '../node_modules/materialize-css/dist/js/materialize.min.js';

export default {
  name: 'app',
  components: {
    NavBar
  }
}
</script>

<style>

</style>
