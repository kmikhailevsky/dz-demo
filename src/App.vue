<script setup>
import { computed } from 'vue';

const currentDate = computed(() => {
  return new Date().toLocaleDateString('ru-RU', {
    year: 'numeric',
    month: 'long',
    day: 'numeric'
  });
});
</script>

<template>
  <div class="box">
    <h1>{{ currentDate }}</h1>
  </div>
</template> 

<style scoped>
  .box {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-size: 4rem;
  }

</style>