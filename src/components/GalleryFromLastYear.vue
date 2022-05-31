<template>
  <div id="gallery-from-last-year" class="item d-flex flex-column">
          <h5>{{galleryFromLastYear.title}}</h5>
          <div id="gallery" class="d-flex flex-wrap justify-content-between">
            <img
            v-for="(image, index) in galleryFromLastYear.images" :key="`image-${index}`"
            v-bind="require('../assets/images/' + image)" alt="index">
          </div>
        </div>
</template>

<script>
export default {
name: 'GalleryFromLastYear',
props: {
  galleryFromLastYear: Object
}
}
</script>

<style>

</style>