<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import BottomMain from './components/BottomMain.vue';


export default{
  components: {
    AppHeader,
    AppMain,
    BottomMain
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
</template>

<style lang="scss">
@use './style/generic' as *
</style>
