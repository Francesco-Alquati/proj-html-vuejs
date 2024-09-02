<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainMiddle from './components/AppMainMiddle.vue';
import AppMainBottom from './components/AppMainBottom.vue';

export default{
  components:{
    AppHeader,
    AppJumbo,
    AppMainTop,
    AppMainMiddle,
    AppMainBottom,
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
    <AppMainBottom />
  </main>
  <footer>

  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
