<template>
  <Navbar />
  <Slide />
  <Card />
  <Me />
  <Talk />
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Me from "./components/Me.vue";
import Card from "./components/Card.vue";
import Slide from "./components/Slide.vue";
import Talk from "./components/Talk.vue";
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap");

#app {
  font-family: "ubuntu", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
