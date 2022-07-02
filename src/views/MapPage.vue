<template>
  <Navbar></Navbar>
  <div class="test container text-center">地圖內容</div>
</template>

<script>
import Navbar from "../components/CatNavbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>

<style>
.test {
  height: 500px;
}
</style>
