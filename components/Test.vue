<template>
  <div>
    <div v-if="navi === 2">123</div>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  navi: number;
}>();
</script>

<style scoped lang="scss"></style>
