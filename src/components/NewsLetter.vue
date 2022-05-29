<template>
  <section class="d-flex flex-column align-items-center justify-content-center">
    <div id="timer" class="d-flex justify-content-center">
      <div id="days" class="square px-4">
        <div class="number">3399</div>
        <div class="text">days</div>
      </div>
      <div id="hours" class="square">
        <div class="number">17</div>
        <div class="text">hours</div>
      </div>
      <div id="mins" class="square">
        <div class="number">28</div>
        <div class="text">mins</div>
      </div>
      <div id="secs" class="square">
        <div class="number">17</div>
        <div class="text">secs</div>
      </div>
    </div>

    <p>SUBSCRIBE FOR UPDATES</p>

    <div id="form" class="d-flex">
      <input type="email" class="form-control mx-4" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Please fill your email">
      <button type="button" class="btn btn-danger">SUBSCRIBE</button>
    </div>
  </section>
</template>

<script>
export default {
name: 'NewsLetter'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  background-image: url('../assets/images/coutdown-bg1.jpg');
  background-position: center;
  background-size:auto;
  padding: 100px 0 80px 0;
  .square{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-transform: uppercase;
    padding: 10px 45px 25px 45px;
    margin: 0 0 40px 20px;
    border-radius: 5px;
    color: $white;
    font-weight: 700;
    .number{
      font-size: 55px;
    }
    .text{
      font-weight: 500;
    }
    &#days{
      background-color: rgba($color: $mine-shaft, $alpha: .9);
    }
    &#hours{
      background-color: rgba($color: $mine-shaft, $alpha: .80);
    }
    &#mins{
      background-color: rgba($color: $mine-shaft, $alpha: .75);
    }
    &#secs{
      background-color: rgba($color: $mine-shaft, $alpha: .7);
    }
  }
  p{
    font-weight: bold;
    font-size: 22px;
    letter-spacing: 2px;
    margin-bottom: 30px;
  }
  input{
    font-size: 0.8rem;
    padding: 15px 25px;
    width: 400px;
    border-radius: 0;
  }
  button{
    font-size: 0.9rem;
    font-weight: bold;
    background-color: $scarlet;
    padding: 0 30px;
  }
}
</style>