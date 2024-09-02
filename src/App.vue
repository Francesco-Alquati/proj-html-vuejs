<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainMiddle from './components/AppMainMiddle.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppUsersReview from './components/AppUsersReview.vue';

export default{
  components:{
    AppHeader,
    AppJumbo,
    AppMainTop,
    AppMainMiddle,
    AppMainBottom,
    AppUsersReview,
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
    <AppMainMiddle />
    <AppMainBottom />
    <AppUsersReview />
  </main>
  <footer>

  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
