<template>
  <div id="app">
    <FirstTraning/>
  </div>
</template>

<script>
import FirstTraning from "@/components/FirstTraning";

export default {
  name: 'App',
  components: {
    FirstTraning
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
