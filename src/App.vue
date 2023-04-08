<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="center">
    <h2>Beesense</h2>
    <span>Děláme data</span>
  </div>
</template>

<style lang="scss" scoped>
.center {
  height: 100vh;
  position: relative;
}
span {
  position: absolute;
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: "Dancing Script", sans-serif;
  font-size: 22px;
}
h2 {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: "Inter", sans-serif;
  font-size: 4rem;
  font-weight: 500;
  background: linear-gradient(to right, #cf4a30 0%, #655dcf 83%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  @media (min-width: 768px) {
    font-size: 6rem;
  }
}
</style>
