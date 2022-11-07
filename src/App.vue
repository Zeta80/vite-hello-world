

<script >
import AppJumbo from "./components/AppJumbo.vue";
export default {
  data() {
    return {
      message: "La mia prima app con Vite!"
    }
  },
  components: {
    AppJumbo
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

  <AppJumbo />

</template>

<style >

</style>
