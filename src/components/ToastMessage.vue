<script setup>
import { ref } from 'vue'
const isLogin = ref(false)
</script>

<template>
  <div class="toast" role="alert" aria-live="assertive" aria-atomic="true" v-show="isLogin">
    <div class="toast-body">登入成功</div>
  </div>
</template>
