# componente mostrará la fecha del tweet.
<script lang="ts" setup>
defineProps({
  date: String
});
</script>

<template>
  <span>{{ date }}</span>
</template>

<style scoped>
span {
  color: gray;
  margin-left: 5px;
}
</style>
