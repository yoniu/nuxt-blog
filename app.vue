<script lang="ts" setup>
  const { data } = await useFetch(`https://testing.200011.net/`)
</script>

<template>
  <div v-html="data">
  </div>
</template>
