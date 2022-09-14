<script setup>
import QR from "./components/QR.vue"
</script>

<template>
    <QR></QR>
</template>

<style lang="scss">
  /* @import "./assets/styles/global.scss" */
  @import "./assets/styles/variables.scss";
  @import "./assets/styles/font.scss";

  body {
    background-color: var(--bg-body);
    margin: 0;
    min-height: 100vh;
    min-width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
