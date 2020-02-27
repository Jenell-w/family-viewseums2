<template>
  <div id="app">
    <img alt="Museum app icon" src="./assets/museum-plain.png" />
    <MuseumInfo msg="Family ViewSeums" />
  </div>
</template>

<script>
import MuseumInfo from "./components/MuseumInfo.vue";

export default {
  name: "App",
  components: {
    MuseumInfo
  }
};
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
