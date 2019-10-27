<template>
  <div id="app">
    <app-title id="main" />
    <!-- <div class = 'whiteSpace'/> -->
    <social-media />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import SocialMedia from "./components/SocialMedia.vue";

export default {
  components: {
    appTitle: Title,
    SocialMedia
  }
};
</script>

<style>
@import "https://use.fontawesome.com/releases/v5.6.3/css/all.css";

#app {
  font-family: "Raptor";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: url("https://raw.githubusercontent.com/nspilman/sacgeo/master/src/assets/images/swirlyBro.gif");
  background-repeat: no-repeat;
  background-position: 50%, 50%;
  background-attachment: fixed;
  background-color: black;
  height: 100vh;
  width: 100%;
}

#main {
  min-height: 100%;
  margin-bottom: -100px;
}

.whiteSpace {
  height: 80%;
}
</style>
