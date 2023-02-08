<template>
  <div>
    <Test :navi="navi" />
    222
    <slot />
  </div>
</template>

<script setup lang='ts'>
const navi = useNavi()
</script>

<style scoped lang='scss'>
</style>