<template>
  <div>
    <div v-if="isShow">
      Скрываемый блок
    </div>
    <button @click="isShow = true">Показать</button>
    <button @click="isShow = false">Скрыть</button>
  </div>
</template>

<script>
export default {
  name: "Conditional",
  data() {
    return {
      isShow: true
    }
  }
}
</script>

<style scoped>

</style>