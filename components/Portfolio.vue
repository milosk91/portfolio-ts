<template>
  <div class="app">
    <AboutPagePortfolio />
    <div>
      <el-button class="button" plain @click="goToHome()">
        <img src="/mk-logo-rosybrown.png" class="logo" />
      </el-button>
    </div>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import AboutPagePortfolio from './AboutPagePortfolio.vue'

@Component({
  components: {
    AboutPagePortfolio,
  },
})
export default class Portfolio extends Vue {
  /* Props */
  /* State */
  /* Data */
  /* Hooks */
  /* Methods */
  goToHome(): void {
    this.$router.push('/home')
  }
  /* Computed */
  /* Watchers */
}
</script>

<style scoped>
.app body html {
  height: 100%;
  width: 100%;
}

.logo {
  position: relative;
  display: block;
  margin: 30px;
  top: 0px;
  left: 0px;
  width: 85px;
  height: 50px;
  fill: rgb(188, 143, 143);
}

.button {
  position: absolute;
  top: 0px;
  left: 0px;
  border: none;
  /* background: #f6f6f6; */
}
.button :hover {
  background: #fff;
}
</style>
