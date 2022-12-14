<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>

<script>

export default {
  data() {
    return {
      count: 1
    }
  }
}
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>