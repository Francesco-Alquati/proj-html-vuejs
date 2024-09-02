<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainMiddle from './components/AppMainMiddle.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppUsersReview from './components/AppUsersReview.vue';
import AppNewsBlog from './components/AppNewsBlog.vue';
import AppSponsor from './components/AppSponsor.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';

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
    AppFooterTop,
    AppFooterBottom,
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
    <AppFooterTop />
    <AppFooterBottom />
  </footer>
</template>

<style lang="scss">
@import './styles/generals.scss';

</style>
