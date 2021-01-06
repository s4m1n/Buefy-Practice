<template>
  <div class="hero is-dark is-fullheight is-bold">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title">{{ title }}</h1>
        <p class="is-size-4">{{ msg }}</p>
        <a href="#contactForm"
          ><b-button class="mt-10" type="is-primary">Contact us</b-button></a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    title: String,
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.mt-10 {
  margin-top: 10px;
}
</style>
