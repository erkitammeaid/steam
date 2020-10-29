<template>
  <primary-nav />
  <secondary-nav />
</template>
<script>
import PrimaryNav from "./components/PrimaryNav.vue";
import SecondaryNav from "./components/SecondaryNav.vue";
import background from "./components/background.vue";
import links from "./components/links.vue";

export default {
  name: "App",
  components: {
    PrimaryNav,
    SecondaryNav,
    background,
    links,
  },
};
</script>
<style src="./assets/tailwind.css"> </style>
