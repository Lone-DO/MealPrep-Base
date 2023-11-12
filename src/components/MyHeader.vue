<template>
  <header id="my-header">
    <i class="fa-solid fa-plate-wheat"></i>
    <h1>MealPrep.org</h1>
  </header>
</template>

<script>
export default {
  name: 'MyHeader',
}
</script>

<style lang="scss">
#my-header {
  gap: 0.5rem;
  display: flex;
  align-items: center;
  svg {
    font-size: 2rem;
  }
}
</style>