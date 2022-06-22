<template>
  <div id="app" class="container">
    <Portfolio />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Router from 'vue-router'
import Portfolio from '~/components/Portfolio.vue'

Vue.use(Router)

export default Vue.extend({
  components: {
    Portfolio,
  },
})
</script>

<style>
* {
  box-sizing: border-box;
  /* background: #f6f6f6; */
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-size: 24px;
}

.logo {
  display: block;
  margin: 20px auto;
  height: 160px;
  width: 190px;
}
</style>
