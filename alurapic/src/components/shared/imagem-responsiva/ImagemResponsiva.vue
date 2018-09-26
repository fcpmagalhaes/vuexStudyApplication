<template>
  <img class="imagem-responsiva" :src="url" :alt="titulo">
  <!-- diretiva v-bind ou seu atalho :bind para interpolação dentro de um atributo -->
</template>

<script>
export default {
  props: ["url", "titulo"]
};
</script>

<style scoped>
.imagem-responsiva {
  width: 100%;
}
</style>
