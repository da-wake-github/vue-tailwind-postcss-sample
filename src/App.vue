<script setup>
import HelloWorld from './components/HelloWorld.vue'
const list = ['おはよう', 'こんにちは', 'こんばんは']
</script>

<template>
  <h1 class="text-3xl font-bold underline bg">
    Hello world!
  </h1>

  <HelloWorld v-for="item in list" :msg=item />

  <a href="#" class="button">ボタン</a>
</template>

<style scoped>
.button {
  @apply border border-green-500 bg-green-500 text-white rounded-md px-4 py-2 m-2;
}
</style>