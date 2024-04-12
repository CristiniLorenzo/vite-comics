<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import BottomMain from './components/BottomMain.vue';
import TopFooter from './components/TopFooter.vue';

export default{
  components: {
    AppHeader,
    AppMain,
    BottomMain,
    TopFooter
  }
}
</script>

<template>
  <header>
    <AppHeader></AppHeader>
  </header>
  
  <main>
  <AppMain></AppMain>
  <BottomMain></BottomMain>
  </main>
  <TopFooter></TopFooter>
</template>

<style lang="scss">
@use './style/generic' as *
</style>
