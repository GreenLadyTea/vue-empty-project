<template>
  <ul>
    <li v-for="(item, key) in list" :key="key">{{item}}</li>
  </ul>
</template>
<script>
export default {
  name: "List",
  data() {
    return {
      list: ["один", "два", "три"]
    }
  }
}
</script>

<style scoped>

</style>