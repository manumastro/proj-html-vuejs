<template>
  <main>
    <JumbotronC />
    <WhoWheAre />
    <NewsLetter />
    <SpeakersC />
    <ProgramC />
    <MapsC />
    <LocationC />
    <RecentNews />
    <TicketsC />
    <PresentationTwitterFeed />
  </main>
</template>

<script>
import JumbotronC from './JumbotronC.vue'
import WhoWheAre from './WhoWheAre.vue'
import NewsLetter from './NewsLetter.vue'
import SpeakersC from './SpeakersC.vue'
import ProgramC from './ProgramC.vue'
import MapsC from './MapsC.vue'
import LocationC from './LocationC.vue'
import RecentNews from './RecentNews.vue'
import TicketsC from './TicketsC.vue'
import PresentationTwitterFeed from './PresentationTwitterFeed.vue'

export default {
  name: 'MainC',
  components: {
    JumbotronC,
    WhoWheAre,
    NewsLetter,
    SpeakersC,
    ProgramC,
    MapsC,
    LocationC,
    RecentNews,
    TicketsC,
    PresentationTwitterFeed
  }
}
</script>
<style lang="scss" scoped>

</style>