# script sobre la imagen del perfil del usuario
<script lang="ts" setup>
defineProps({
  image: String
});
</script>

<template>
  <img src="https://i.imgur.com/9yw1Fyw.jpg" alt="Imagen de perfil" />
</template>

<style scoped>
img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}
</style>
    
