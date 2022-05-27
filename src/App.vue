<template>
  <div>
    <HeaderC />
    <MainC />
  </div>
</template>

<script>
import HeaderC from './components/HeaderC.vue'
import MainC from './components/MainC.vue'

export default {
  name: 'App',
  components: {
    HeaderC,
    MainC
    
  }
}
</script>

<style lang="scss">
@import './assets/style/_general.scss';
@import './assets/style/_vars.scss';

</style>
