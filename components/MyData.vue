<template>
  <div v-html="myData.data"></div>
</template>

<script lang="ts" setup>
  import {reactive} from 'vue-demi'
  const myData = reactive(await useFetch(`https://testing.200011.net/`))
</script>