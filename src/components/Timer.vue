<template>
  <div>
    {{ timer }}
  </div>
</template>

<script>
export default {
  name: "Timer",
  data() {
    return {
      timer: 0
    }
  },
  mounted() {
    this.intervalId = setInterval(() => this.timer = this.timer + 1, 1000);
  },
  unmounted() {
    clearInterval(this.intervalId);
  }
}
</script>

<style scoped>

</style>