<template>
<div>
  <Home/>
  <About/>
  <Shop/>
  <Contact/>
  <!-- <Home/> -->
</div>
</template>

<script>
import Home from "./components/Home/"
import About from "./components/About/"
import Shop from "./components/Shop/"
import Contact from "./components/Contact/"

export default {
  components:{
    Home,
    About,
    Shop,
    Contact
  }
}
</script>
