<template>
  <div class="header">
    <div class="header__left">
        <a href="/catalog" class="header__text text-small">Каталог</a>
        <a class="header__text text-small">Каталог</a>
        <a class="header__text text-small">Каталог</a>
        <a class="header__text text-small">Каталог</a>
    </div>
    <div class="header__middle"></div>
    <div class="header__right"></div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
.header {
  background: var(--main-color);
  &__text{

  }
}
</style>
