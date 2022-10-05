<template>
  <div>
    <header-vue></header-vue>
    <Nuxt />
  </div>
</template>

<script>
import headerVue from "../components/header.vue";
export default {
  components: {
    headerVue,
  },
};
</script>
