<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainMiddle from './components/AppMainMiddle.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppUsersReview from './components/AppUsersReview.vue';
import AppNewsBlog from './components/AppNewsBlog.vue';
import AppSponsor from './components/AppSponsor.vue';

export default{
  components:{
    AppHeader,
    AppJumbo,
    AppMainTop,
    AppMainMiddle,
    AppMainBottom,
    AppUsersReview,
    AppNewsBlog,
    AppSponsor,
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
    <AppNewsBlog />
    <AppSponsor/>
  </main>
  <footer>

  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
