<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainMiddle from './components/AppMainMiddle.vue';

export default{
  components:{
    AppHeader,
    AppJumbo,
    AppMainTop,
    AppMainMiddle,
  }
}
</script>

<template>
  <header>
    <AppHeader />
  </header>
  <AppJumbo />
  <main>
    <AppMainTop />
    <AppMainMiddle />
  </main>
  <footer>

  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
