<template>
  <nav id="navigation">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
</template>

<script>
import { RouterLink } from 'vue-router'

export default { 
  name: 'MyNavigation',
  components: { RouterLink },
}
</script>

<style lang="scss">
  #my-navigation {
    grid-area: nav;
  }
</style>