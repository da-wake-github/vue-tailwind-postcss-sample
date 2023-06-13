<script setup>
defineProps({
  msg: String,
})
</script>

<template>
  <h1 class="bg-red-500 p-10 w-40 m-auto my-5 text-white text-lg text-center hover:opacity-30 transition-opacity duration-1000">
    {{ msg }}
  </h1>
</template>