<template>
  <div>
    <Home />
    <About />
    <Shop />
    <Contact />
    <!-- <Home/> -->
  </div>
</template>

<script>
import Home from "./components/Home/Home.vue";
import About from "./components/About/About.vue";
import Shop from "./components/Shop/Shop.vue";
import Contact from "./components/Contact/Contact.vue";

export default {
  components: {
    Home,
    About,
    Shop,
    Contact
  }
};
</script>
