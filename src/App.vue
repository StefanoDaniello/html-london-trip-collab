<template>
  <HeaderComponent/>
  <CardList/>
  <MainComponent/>
  <FooterComponent/>
  <FooterBottom/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import CardList from './components/CardList.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import FooterBottom from './components/FooterBottom.vue';
  export default {
    name: 'App',
    components: {
        HeaderComponent,
        CardList,
        MainComponent,
        FooterComponent,
        FooterBottom
    },
  }
</script>

<style lang="scss" scoped>

</style>