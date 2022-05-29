<template>
  <div id="wrapper-jumbo" class="d-flex flex-column">
    <div id="jumbotron" class="d-flex flex-column align-items-center justify-content-center">
    <div id="title" class="d-flex align-items-center flex-column pb-5">
      <h2>Conference on</h2>
      <h1>social networks</h1>
    </div>
    <div id="dates" class=" d-flex">
      <h5>23 - 26 MAY 2019</h5>
      <h5>/</h5>
      <h5>Sans Francisco</h5>
      <h5>/</h5>
      <h5>8 Speakers</h5>
    </div>
    <div id="register">
      <a href="#">
        <button type="button" class="btn btn-danger">REGISTER ONLINE</button>
      </a>
    </div>
    </div>

    <div id="info" class="container d-flex justify-content-between align-items-center pt-4">
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
  </div>
</template>

<script>
export default {
name: 'JumbotronC'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
#wrapper-jumbo{
  height: calc(100vh - 110px);
  #jumbotron{
    background-image: url('../assets/images/slider-1-bg.jpg');
    background-position: center;
    background-size: cover;
    padding: 120px 0;
    h1, h2, h3, h5, a{
      color: $white;
      text-transform: uppercase;
    }
    h2{
      letter-spacing: 1px;
      font-size: 58px;
      font-weight: 300;
    }
    h1{
      font-size: 90px;
      font-weight: 600;
    }
    #dates{
      position: relative;
      padding-bottom: 40px;
      h5{
        font-size: 18px;
        margin: 0 10px;
        font-weight: bold;
      }
      &::before{
        content: '';
        position: absolute;
        top: -17px;
        right: 0;
        height: 4px;
        width: 100%;
        background-color: $white;
      }
    }
    button{
      font-weight: bold;
      background-color: $scarlet;
      padding: 15px 30px;
    }
  }
  #info{
    flex-grow: 1;
    padding: 0 90px;
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
}

</style>