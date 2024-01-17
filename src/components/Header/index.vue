<template>
  <div class="navbar">
    <a href="">
      <img class="logo" src="https://www.zpzpup.com/assets/image/avatar.png" alt="" />
      <span class="site-name">杨衡</span>
    </a>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  background-color: rgb(24, 24, 24, 24);
  z-index: 20;
  right: 0;
  height: 3.6rem;
  box-sizing: border-box;
  padding: 0.7rem 1.5rem;
  line-height: 2.2rem;
  box-shadow: var(--box-shadow);
  background: var(--background-color);
  .logo {
    height: 2.2rem;
    min-width: 2.2rem;
    margin-right: 0.8rem;
    vertical-align: top;
    border-radius: 50%;
  }
}
</style>
