<template>
  <main>
    <JumbotronC />
    <NewsLetter />
  </main>
</template>

<script>
import JumbotronC from './JumbotronC.vue'
import NewsLetter from './NewsLetter.vue'
export default {
  name: 'MainC',
  components: {
    JumbotronC,
    NewsLetter
  }
}
</script>

<style lang="scss" scoped>

</style>