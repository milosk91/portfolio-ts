<template>
  <div>
    <HomePagePortfolio />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import HomePagePortfolio from '~/components/HomePagePortfolio.vue'

@Component({
  components: {
    HomePagePortfolio,
  },
})
export default class home extends Vue {
  /* Props */
  /* State */
  /* Data */
  /* Hooks */
  /* Methods */
  /* Computed */
  /* Watchers */
}
</script>

<style scoped>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  /* background: #ececec; */
}
</style>
