<template>
  <div id="app">
<app-title/>
<div class = 'whiteSpace'/>
<social-media/>
   </div>
</template>

<script>
import title from './components/title.vue'
import socialMedia from './components/socialMedia.vue'

export default {
  components: {
appTitle:title,
socialMedia,
  },
}
</script>


<style>

@font-face {
  font-family: 'Raptor';
  src:  url('/assets/fonts/raptor_sans.ttf') format('truetype');
}



#app {
  font-family: "Raptor";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image:url('assets/images/swirlyBro.gif');
  background-repeat: no-repeat;
  background-position: 50%,50%;
  background-attachment: fixed;
  background-color:black;
  height: 100vh;
  width:100%;
}

.whiteSpace{
  height:80%;
}

</style>
