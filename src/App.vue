<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';

export default{
  components:{
    AppHeader,
    AppJumbo,
    AppMainTop
  }
}
</script>

<template>
  <header>
    <AppHeader />
  </header>
  <main>
    <AppJumbo />
    <AppMainTop />
  </main>
  <footer>

  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
