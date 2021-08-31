<template>
  <Header></Header>
  <main-component></main-component>
</template>

<script>
import Header from "./components/Header.vue"
import MainComponent from "./components/MainComponent.vue"
// import WestSide from "./components/WestSide.vue"

export default {
  name: 'App',
  components: {
    Header,
    MainComponent,

  }
}
</script>

<style>
</style>
