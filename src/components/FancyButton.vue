<template>
  <button @click="clickReaction">
    <slot></slot>
  </button>
</template>

<script lang="ts">
export default {
  name: "FancyButton",
  methods: {
    clickReaction() {
      console.log("Clicked!");
    }
  }
}
</script>

<style scoped>

</style>