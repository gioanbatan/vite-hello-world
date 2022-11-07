<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      test: "Hello world!"
    }
  },
  components: {
    AppTitle,
    AppHero,
  },
  methods: {
    testAlert() {
      alert("test");
    }
  }
}
</script>

<template>
  <section class="test-vite">
      <AppTitle />
      <AppHero />
  </section>

  <button @click="testAlert">Test button</button>
</template>

<style>
</style>
