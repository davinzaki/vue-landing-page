<template>
  <nav>
    <navbar />
  </nav>
  <router-view />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: { Navbar, Footer },
};
</script>

<style>
body {
  color: #131313;
}
</style>
