<template>
  <section id="speakers">
    <div class="container wrapper">
      <div class="d-flex justify-content-between align-items-center mb-5">
        <h1>SPEAKERS</h1>
        <div id="buttons">
          <button type="button" class="btn btn-danger">
            <i class="fa-solid fa-chevron-left"></i>
          </button> 
          <button type="button" class="btn btn-danger">
            <i class="fa-solid fa-chevron-right"></i>
          </button> 
        </div>
      </div>
      <div id="speakers" class="d-flex justify-content-between">
        <div class="speaker position-relative">
          <div class="overlay">
            <img src="../assets/images/speaker-6.jpg" alt="">
          </div>
          <div class="socials">
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
          </div>
          <div class="name">PATRICK SPENCER</div>
          <div class="rule">S&P Analyzer</div>
        </div>

        <div class="speaker position-relative">
          <div class="overlay">
            <img src="../assets/images/speaker-5.jpg" alt="">
          </div>
          <div class="socials">
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
          </div>
          <div class="name">JANET JONES</div>
          <div class="rule">Newyork Post's GM</div>
        </div>

        <div class="speaker position-relative">
          <div class="overlay">
            <img src="../assets/images/speaker-4.jpg" alt="">
          </div>
          <div class="socials">
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
          </div>
          <div class="name">MICHAEL DOVER</div>
          <div class="rule">Starbuck's CEO</div>
        </div>

        <div class="speaker position-relative">
          <div class="overlay">
            <img src="../assets/images/speaker-3.jpg" alt="">
          </div>
          <div class="socials">
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
          </div>
          <div class="name">ANGELINA HOLY</div>
          <div class="rule">Maxii's Manager</div>
        </div>
        
        
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  padding: 80px 0;
  background-color: #f3f3f3;
  .wrapper{
    padding: 0 100px;
    h1{
      font-weight: bold;
    }
    button{
      padding: 5px 15px;
      margin: 0 3px;
      background-color: $scarlet;
      i{
        font-size: 0.6rem;
      }
    }
  }
  .speaker{
    width: 23%;
    display: flex;
    flex-direction: column;
    align-items: center;
    &:hover img{
      opacity: 0.3;
    }
    &:hover .socials{
      opacity: 1;
    }
    &:hover .overlay{
      background: #e9624c;
    }
    img{
      transition: .5s ease;
      width: 100%;
      border-radius: 5px;
    }
    .overlay{
      transition: .5s ease-in-out;
      max-height: 186px;
      margin-bottom: 22px;
      border-radius: 5px;
    }
    .socials{
      transition: .5s ease;
      opacity: 0;
      position: absolute;
      top: 36%;
      left: 50%;
      transform: translate(-50%, -50%);
      i{
        margin-right: 15px;
        color: white;
        font-size: 19px;
      }
    }
    .name{
      font-weight: 600;
      letter-spacing: 2px;
      margin-bottom: 8px;
    }
    .rule{
      font-size: 0.8rem;
      font-style: italic;
      font-weight: 600;
      color: $gray;
    }
  }
}
</style>