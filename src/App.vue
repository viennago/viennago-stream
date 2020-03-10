<template>
  <div id="app">
    <img alt="vienna.go (Golang) logo" src="./assets/logo.png" class="logo-image">
    <StreamInfo />
  </div>
</template>

<script>
import StreamInfo from './components/StreamInfo'

export default {
  name: 'App',
  components: {
    StreamInfo
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
.logo-image {
  height: 150px;
}
</style>
