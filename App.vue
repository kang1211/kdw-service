<script setup>
import { ref } from 'vue'

// 반응형 상태(State) 정의
const message = ref('안녕하세요! Vue 프로젝트가 정상적으로 실행되었습니다.')
</script>

<template>
  <main class="app-container">
    <h1>{{ message }}</h1>
    <p>이 화면은 src/App.vue 파일에서 렌더링되고 있습니다.</p>
  </main>
</template>

<style scoped>
.app-container {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  text-align: center;
  margin-top: 60px;
  color: #2c3e50;
}

h1 {
  font-size: 24px;
  margin-bottom: 10px;
}
</style>