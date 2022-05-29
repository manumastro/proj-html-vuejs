<template>
  <main>
    <JumbotronC />
    <NewsLetter />
    <ProgramC />
  </main>
</template>

<script>
import JumbotronC from './JumbotronC.vue'
import NewsLetter from './NewsLetter.vue'
import ProgramC from './ProgramC.vue'
export default {
  name: 'MainC',
  components: {
    JumbotronC,
    NewsLetter,
    ProgramC
  }
}
</script>

<style lang="scss" scoped>

</style>