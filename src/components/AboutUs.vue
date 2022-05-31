<template>
  <div id="about-us" class="d-flex flex-column item">
          <h5>{{aboutUs.title}}</h5>
          <p>{{aboutUs.description}}</p>
          <div id="socials" class="d-flex">
            <a
            v-for="(icon, index) in aboutUs.icons" :key="`icon-${index}`" 
            href="#">
            <i :class="`${icon}`"></i>
            </a>
          </div>
        </div>
</template>

<script>
export default {
name: 'AboutUs',
props: {
  aboutUs: Object,
}
}
</script>

<style>

</style>