<script setup>
import { ref } from 'vue'

const currentTime = ref(Date.now());
</script>

<template>
  <div class="box">
    <h1>15.03.2026</h1>
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