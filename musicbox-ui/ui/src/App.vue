<template>
  <div id="app">
    <MusicBoxNavbar />
    <img src="./assets/musicbox.jpg" />
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import MusicBoxNavbar from "./components/navbar/MusicBoxNavbar";
export default {
  name: "app",
  components: { MusicBoxNavbar },
  data() {
    return {
      msg: "Welcome to Music Box App",
    };
  },
};
</script>

<style lang="scss">
</style>
