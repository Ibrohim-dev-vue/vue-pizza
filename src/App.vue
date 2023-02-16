<template>
  <navbar />
  <router-view />
</template>

<style></style>

<script>
import navbar from "./components/navbar.vue";

export default {
  name: "HomeView",
  components: {
    navbar,
  },
};
</script>
