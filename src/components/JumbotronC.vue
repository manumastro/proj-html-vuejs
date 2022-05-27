<template>
  <div class="jumbotron d-flex flex-column align-items-center justify-content-center">
    <div class="title d-flex align-items-center flex-column pb-5">
      <h2>Conference on</h2>
      <h1>social networks</h1>
    </div>
    <div class="dates d-flex">
      <h5>23 - 26 MAY 2019</h5>
      <h5>/</h5>
      <h5>Sans Francisco</h5>
      <h5>/</h5>
      <h5>8 Speakers</h5>
    </div>
    <div class="register">
      <a href="#">
        <button type="button" class="btn btn-danger">REGISTER ONLINE</button>
      </a>
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
.jumbotron{
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
  .dates{
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
</style>