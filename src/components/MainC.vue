<template>
  <main>
    <JumbotronC />
    <NewsLetter />
    <SpeakersC />
    <ProgramC />
  </main>
</template>

<script>
import JumbotronC from './JumbotronC.vue'
import NewsLetter from './NewsLetter.vue'
import SpeakersC from './SpeakersC.vue'
import ProgramC from './ProgramC.vue'
export default {
  name: 'MainC',
  components: {
    JumbotronC,
    NewsLetter,
    SpeakersC,
    ProgramC
  }
}
</script>

<style lang="scss" scoped>

</style>