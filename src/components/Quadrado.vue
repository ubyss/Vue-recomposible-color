<template>
  <div class="hello">
    <div class="bloco" :style="{ background: '#' + cor }"></div>
  </div>
</template>

<script>
export default {
  name: "Quadrado",
  props: {
    msg: String,
    cor: String,
  },
};
</script>


<style>
.bloco {
  width: 200px;
  height: 200px;
  /* background: #000000; */
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
