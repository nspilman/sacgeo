<template>
<div>
  <Home/>
  <About/>
  <Shop/>
  <!-- <Home/> -->
</div>
</template>

<script>
import Home from "./components/Home/"
import About from "./components/About/"
import Shop from "./components/Shop/"

export default {
  components:{
    Home,
    About,
    Shop
  }
}
</script>
