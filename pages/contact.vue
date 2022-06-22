<template>
  <div>
    <ContactPagePortfolio />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import ContactPagePortfolio from '~/components/ContactPagePortfolio.vue'

@Component({
  components: {
    ContactPagePortfolio,
  },
})
export default class contact extends Vue {
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
