<template>
  <div id="app">
<app-title id ="main"/>
<!-- <div class = 'whiteSpace'/> -->
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
@import 'https://use.fontawesome.com/releases/v5.6.3/css/all.css';

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

#main{
  min-height:100%;
  margin-bottom:-100px;
}

.whiteSpace{
  height:80%;
}

</style>
