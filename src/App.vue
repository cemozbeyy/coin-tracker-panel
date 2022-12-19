<template>
  <div>
    <Dashboard />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

import Dashboard from './components/Dashboard.vue';

@Options({
  components: {
    Dashboard
  },
})
export default class App extends Vue {

  beforeMount() {

  }
}
</script>

<style>

</style>
