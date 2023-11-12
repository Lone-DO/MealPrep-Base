<template>
  <MyHeader />
  <MyNavigation />
  <main id="content">
    <RouterView />
  </main>
</template>

<script>
import { RouterView } from 'vue-router'
import MyHeader from './components/MyHeader.vue'
import MyNavigation from './components/MyNavigation.vue'

export default {
  components: { RouterView, MyHeader, MyNavigation },
}

</script>

<style lang='scss'>
#app {
  padding: 2rem;
  margin: 0 auto;
  max-width: 1280px;
  font-weight: normal;

  @media (min-width: 1024px) {
    display: grid;
    padding: 0 2rem;
    grid-template-columns: 1fr 1fr;
    grid-template-areas: "nav header" "nav main";
  }
}

</style>
