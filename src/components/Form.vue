<template>
  <div>
    <input v-model="value"/>
    Вы ввели: {{ value }}
    <button @click="value = '123'">Изменить стейт</button>
  </div>
</template>

<script>
export default {
  name: "Form",
  data() {
    return {
      value: ""
    }
  }
}
</script>

<style scoped>

</style>