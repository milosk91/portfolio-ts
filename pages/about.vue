<template>
  <div>
    <AboutPagePortfolio />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import AboutPagePortfolio from '~/components/AboutPagePortfolio.vue'

@Component({
  components: {
    AboutPagePortfolio,
  },
})
export default class about extends Vue {
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
