<template>
  <div>
    {{ value }}
  </div>
</template>

<script>
export default {
  name: "Child",
  props: {
    value: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>

</style>