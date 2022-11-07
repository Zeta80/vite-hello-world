

<script >
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      message: "La mia prima app con Vite!"
    }
  },
  components: {
    AppHero
  },
  methods: {
    saluta() {
      alert("ciao");
    }
  }
}

</script>

<template>
  <h1>{{ message }}</h1>
  <AppHero />
</template>

<style >

</style>