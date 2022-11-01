<template>
  <CardVue />
</template>

<script>
import CardVue from './components/CardVue.vue'

export default {
  name: 'App',
  components: {
    CardVue
  }
}
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  height: 100vh;
  align-items: center;
}
</style>
