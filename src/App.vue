<template>
  <div>
    <HeaderC :navElements = nav />
    <MainC />
    <FooterC />
  </div>
</template>

<script>
import HeaderC from './components/HeaderC.vue'
import MainC from './components/MainC.vue'
import FooterC from './components/FooterC.vue'

export default {
  name: 'App',
  components: {
    HeaderC,
    MainC,
    FooterC
  },
  data(){
    return{
      nav: 
      [
        {
          name: 'home',
          isActive: true    
        },
        {
          name: 'pages',
          isActive: false    
        },
        {
          name: 'program',
          isActive: false    
        },
        {
          name: 'tickets',
          isActive: false    
        },
        {
          name: 'speakers',
          isActive: false   
        },
        {
          name: 'papersfalse',
          isActive: false   
        },
        {
          name: 'blog',
          isActive: false   
        },
        {
          name: 'shortcodes',
          isActive: false   
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import './assets/style/_general.scss';
@import './assets/style/_vars.scss';

</style>
