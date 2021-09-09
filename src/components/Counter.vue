<template>
  <button @click="counter += 1">Нажали раз: {{counter}}</button>
</template>
<script>
export default {
  name: "Counter",
  data() {
    return {
      counter: 0
    }
  }
}
</script>

<style scoped>

</style>