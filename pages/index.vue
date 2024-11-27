<template>
  <div>
    <h1 class="text-red-500">Welcome to the homepage</h1>
    <n-button>Default</n-button>
    <div>
      <button @click="setLocale('en')">en</button>
      <button @click="setLocale('vi')">vi</button>
      <p>{{ $t('welcome') }}</p>
    </div>
  </div>
</template>

<script setup lang="ts">
const { setLocale } = useI18n()

</script>

<style scoped>

</style>