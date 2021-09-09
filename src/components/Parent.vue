<template>
  <Child value="42"/>
</template>

<script>
import Child from "./Child";

export default {
  name: "Parent",
  components: { Child }
}
</script>

<style scoped>

</style>