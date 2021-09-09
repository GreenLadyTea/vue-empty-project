<template>
  <div>{{inputString.split("").reverse().join("")}}</div>
</template>
<script>
export default {
  name: "Reverser",
  data() {
    return {
      inputString: "Привет!1234"
    }
  }
}
</script>