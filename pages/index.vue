<template>
  <div class="contaner">
    <left-sidebad></left-sidebad>
    <middle-sidebar></middle-sidebar>
  </div>
</template>

<script>
import LeftSidebad from "../components/leftSidebad.vue";
import MiddleSidebar from "../components/middleSidebar.vue";
export default {
  name: "IndexPage",
  components: {
    LeftSidebad,
    MiddleSidebar,
  },
};
</script>

<style>
.contaner {
  height: calc(100vh - 70px);
  display: flex;
  overflow: hidden;
  background: #f9f9f9;
}
</style>
