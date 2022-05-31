<template>
  <div id="recent-news" class="item">
          <h5>{{recentNews.title}}</h5>
          <div id="links" class="d-flex flex-column ps-2">
            <div
            v-for="(element, index) in recentNews.links" :key="`element-${index}`" 
            class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">{{element}}</a></span>
            </div>
            <!-- <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div>
            <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div>
            <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div>
            <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div> -->
          </div>
        </div>
</template>

<script>
export default {
name: 'RecentNewsFooter',
props: {
  recentNews: Object,
}
}
</script>

<style>

</style>