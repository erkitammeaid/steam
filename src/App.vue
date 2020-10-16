<template>
  <primary-nav />
  <secondary-nav />
</template>
<script>
import PrimaryNav from "./components/PrimaryNav.vue";
import SecondaryNav from "./components/SecondaryNav.vue";
import background from "./components/background.vue";

export default {
  name: "App",
  components: {
    PrimaryNav,
    SecondaryNav,
    background,
  },
};
</script>
<style src="./assets/tailwind.css"> </style>
