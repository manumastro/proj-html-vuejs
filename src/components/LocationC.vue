<template>
  <section class="d-flex flex-column align-items-center justify-content-center">
    <h1 class="pb-4">LOCATION</h1>
    <h3 class="pb-1">GD BUILDING, GRAND CONFERENCE ROOM</h3>
    <span class="pb-3">
      <i class="fa-solid fa-location-arrow me-2"></i>
      11 GD Building, River Mall, New york, USA 8879
    </span> <br>
    <a class="pb-5" href="#">Check For Accomodations Here</a>

    <div id="contacts">
      <i class="fa-solid fa-phone pe-2"></i> 
      <span class="pe-4">+1-112-222-3344</span>

      <i class="fa-solid fa-envelope pe-2"></i>
      <span>Contact@TheKeynoteTheme.com</span>
    </div>
  </section>
</template>

<script>
export default {
name: 'LocationC'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  padding: 100px 0 80px 0;
  background-image: url('../assets/images/location-bg.jpg');
  background-position: center;
  background-size: cover;
  color: $white;
  h1, h3{
    font-weight: 600;
  }
  a{
    color: $scarlet;
  }
}
</style>