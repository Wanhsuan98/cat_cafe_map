<template>
  <Navbar></Navbar>
  <router-view />
  <Footer></Footer>
</template>

<script>
import Navbar from "./components/CatNavbar.vue";
import Footer from "./components/CatFooter.vue";
export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style></style>
