<template>
  <div id="app">
    <Hero msg="Lorem ipsum dolor emet" title="Welcome to Your Vue.js App" />
    <Contact title="Contact Us" />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Contact from "./components/Contact.vue";

export default {
  name: "App",
  components: {
    Hero,
    Contact,
  },
};
</script>


