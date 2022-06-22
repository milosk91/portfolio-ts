<template>
  <div>
    <ProjectsPortfolio />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
import ProjectsPortfolio from '~/components/ProjectsPortfolio.vue'

@Component({
  components: {
    ProjectsPortfolio,
  },
})
export default class projects extends Vue {
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
