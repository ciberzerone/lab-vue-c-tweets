# componente mostrará el nombre del usuario y su handle de Twitter.
<script lang="ts" setup>
defineProps({
  name: String,
  handle: String
});
</script>

<template>
  <div class="user-info">
    <strong>{{ name }}</strong> <span>{{ handle }}</span>
  </div>
</template>

<style scoped>
.user-info {
  display: flex;
  align-items: center;
}
strong {
  margin-right: 5px;
}
span {
  color: gray;
}
</style>
