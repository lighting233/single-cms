<template>
  <div class="login">
    <login-panel> </login-panel>
  </div>
</template>

<script setup lang="ts">
//commitizen
import LoginPanel from './c-cpns/login-panel.vue'
</script>

<style lang="less" scoped>
.login {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url(@/assets/img/login-bg.svg);
}
</style>
