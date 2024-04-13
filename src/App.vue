<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import BottomMain from './components/BottomMain.vue';
import TopFooter from './components/TopFooter.vue';
import AppHero from './components/AppHero.vue';

export default{
  components: {
    AppHeader,
    AppMain,
    BottomMain,
    TopFooter,
    AppHero
  }
}
</script>

<template>
  <header>
    <AppHeader></AppHeader>
  </header>
  <AppHero></AppHero>
  <main>
  <AppMain></AppMain>
  <BottomMain></BottomMain>
  </main>
  <TopFooter></TopFooter>
</template>

<style lang="scss">
@use './style/generic' as *
</style>
