<template>
  <div id="info" class="container d-flex justify-content-between align-items-center">
    <div id="who-we-are" class="d-flex px-3">
      <div class="icon"><i class="fa-solid fa-trophy"></i></div>
      <div class="body">
        <div class="title">WHO WE ARE</div>
        <div class="description"> Donec id elit non mi porta gravida at eget me tus. Sed posuere consectetur estat lobo rtis. Cum sociis natoque.</div>
        <a href="#">Learn More</a>
      </div>
    </div>
    <div id="what-we-do" class="d-flex px-3">
      <div class="icon"><i class="fa-solid fa-bolt-lightning"></i></div>
      <div class="body">
        <div class="title">WHAT WE DO</div>
        <div class="description"> Donec id elit non mi porta gravida at eget me tus. Sed posuere consectetur estat lobo rtis. Cum sociis natoque.</div>
        <a href="#">Learn More</a>
      </div>
      </div>
    <div id="why-us" class="d-flex px-3">
      <div class="icon"><i class="fa-solid fa-question"></i></div>
      <div class="body">
        <div class="title">WHY US?</div>
        <div class="description"> Donec id elit non mi porta gravida at eget me tus. Sed posuere consectetur estat lobo rtis. Cum sociis natoque.</div>
        <a href="#">Learn More</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
#info{
    flex-grow: 1;
    padding: 70px 0 60px 90px;
    i{
      color: $cloud;
      font-size: 25px;
      margin-right: 25px;
    }
    .title{
      color: $mine-shaft;
      font-size: 14px;
      font-weight: bold;
      margin-bottom: 15px;
      letter-spacing: 1px;
    }
    .description{
      color: $gray;
      font-size: 13px;
      letter-spacing: 1px;
      margin-bottom: 25px;
    }
    a{
      color: $froly;
      font-family: 'Times New Roman', Times, serif;
      font-size: 17px;
      font-style: oblique;
      font-weight: 600;
    }
    
  }
</style>