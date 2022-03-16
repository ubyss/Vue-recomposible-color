<template>
  <div id="app">
    <label
      >Cor em Hexadecimal:
      <input type="text" v-model="cor" />
    </label>
    <Quadrado :cor="cor" />
  </div>
</template>

<script>
import Quadrado from "./components/Quadrado";

export default {
  data() {
    return {
      cor: "000000",
    };
  },
  name: "App",
  components: {
    Quadrado,
  },
};
</script>

<style>
</style>
