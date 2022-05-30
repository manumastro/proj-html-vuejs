<template>
  <main>
    <JumbotronC />
    <NewsLetter />
    <SpeakersC />
    <ProgramC />
    <MapsC />
    <LocationC />
  </main>
</template>

<script>
import JumbotronC from './JumbotronC.vue'
import NewsLetter from './NewsLetter.vue'
import SpeakersC from './SpeakersC.vue'
import ProgramC from './ProgramC.vue'
import MapsC from './MapsC.vue'
import LocationC from './LocationC.vue'
export default {
  name: 'MainC',
  components: {
    JumbotronC,
    NewsLetter,
    SpeakersC,
    ProgramC,
    MapsC,
    LocationC
  }
}
</script>

<style lang="scss" scoped>

</style>