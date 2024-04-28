<template>
  <CustomLink />
  <NativeLink />
</template>

<script>
import CustomLink from './components/CustomLink.vue';
import NativeLink from './components/NativeLInk.vue'

export default {
  name: 'App',
  components: {
    CustomLink,
    NativeLink
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
