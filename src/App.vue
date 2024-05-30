<template>
  <div id="app">
    <h2>home</h2>
    <router-link to="/main">主要</router-link>
    <router-link to="/login">登录</router-link>
    <router-view />
  </div>
</template>

<script lang="ts" setup></script>

<style lang="less" scoped>
#app {
  width: 100vw;
  height: 100vh;
}
</style>
