<template>
  <HeaderComponent/>
  <MainTop/>
  <MainComponent/>
  <FooterComponent/>
  <FooterBottom/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainTop  from './components/MainTop.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import FooterBottom from './components/FooterBottom.vue';
  export default {
    name: 'App',
    components: {
        HeaderComponent,
        MainTop,
        MainComponent,
        FooterComponent,
        FooterBottom
    },
  }
</script>

<style lang="scss" scoped>

</style>