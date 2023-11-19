<template>
  <div class="home-page">
    <div class="home-page__header">
      <Header />
    </div>
  </div>
</template>

<script setup>
import Header from "../components/BaseHeader.vue";
</script>

<style lang="scss" scoped>
p {
  font-size: var(--header-font-size);
}
</style>
