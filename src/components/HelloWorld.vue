<script setup lang="ts">
const iOClick: any = () => {
  window.electronAPI.longTimeBlocking().then(res => {
    console.log(res);
  })
}
</script>

<template>
  <button type="button" @click="iOClick">iOClick</button>
</template>

<style scoped></style>
