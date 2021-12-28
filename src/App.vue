<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <BozhidarTestPackage/>
</template>

<script>
import BozhidarTestPackage from 'bozhidar-test-package'

export default {
  name: 'App',
  components: {
    BozhidarTestPackage
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
