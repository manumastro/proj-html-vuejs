<template>
  <footer>
    <section id="top">
      <div class="d-flex justify-content-between container wrapper">
        <div id="about-us" class="d-flex flex-column item">
          <h5>ABOUT US</h5>
          <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
          <div id="socials" class="d-flex">
            <a href="#"><i class="fa-brands fa-facebook-square"></i></a>
            <a href="#"><i class="fa-brands fa-twitter-square"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            <a href="#"><i class="fa-brands fa-google-plus-square"></i></a>
            <a href="#"><i class="fa-brands fa-pinterest-square"></i></a>
          </div>
        </div>
        <div id="recent-news" class="item">
          <h5>RECENT NEWS</h5>
          <div id="links" class="d-flex flex-column ps-2">
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
            </div>
            <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div>
            <div class="link d-flex align-items-center">
              <i class="fa-solid fa-chevron-right"></i>
              <span><a href="#">SEM PORTA MOLLIS PARTURIENT</a></span>
            </div>
          </div>
        </div>
        <div id="get-your-seat" class="item d-flex flex-column">
          <h5>GET YOUR SEAT!</h5>
          <p>Book for your seat before it's too rate. <br> We provide variety of ticket options</p>
          <button class="btn btn-danger"><a href="#">CHECK OUT TICKETS!</a></button>
        </div>
        <div id="gallery-from-last-year" class="item d-flex flex-column">
          <h5>GALLERY FROM LAST YEAR</h5>
          <div id="gallery" class="d-flex flex-wrap justify-content-between">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
            <img src="../assets/images/6426608875_186070f8ca_o-150x150.jpg" alt="">
          </div>
        </div>
      </div>
    </section>

    <section id="bottom">
      <div class="d-flex container justify-content-between wrapper">
        <span id="copyright">
          <i class="fa-solid fa-copyright"></i>
          Copyright GoodLayers, All Right Reserved
        </span>
        <span>
          <a href="#">About Us | </a>
          <a href="#">Accommodation | </a>
          <a href="#">Call For Paper | </a>
          <a href="#">Contact Us </a>
        </span>
      </div>
    </section>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';

footer{
  .wrapper{
    padding: 0 100px;
  }
  section#top{
    h5{
    font-size: 13px;
    font-weight: 500;
    letter-spacing: 1.5px;
    color: $white;
    margin-bottom: 25px;
    }
    p{
      font-size: 14px;
      color: $cloud;
    }
    a{
      color: $gray;
    }
    i{
      color: $white;
      font-size: 25px;
      margin-right: 10px;
    }
    button{
      background-color: $scarlet;
      width: 70%;
      border-radius: 0;
      padding: 10px 0;
      a{
        font-size: 13px;
        color: $white;
        font-weight: bold;
      }
    }
    padding: 60px 0;
    background-color: #212121;
    .item{
      width: 22%;
      #gallery{
        img{
          width: calc((100% / 4) - 8px);
          padding-bottom: 10px;
        }
      }
      .link{
        margin-bottom: 16px;
        span{
          font-size: 12px;
        }
        i{
          color: $gray;
          font-size: 8px;
          margin-right: 10px;
        }
      }
    }
  }
  section#bottom{
    background-color: #161616;
    padding: 30px 0;
    i, span, a{
      font-size: 13px;
      color: $gray;
    }
    #copyright{
      color: rgb(85, 84, 84);
      i{
        color: rgba(85, 84, 84, .5);
      }
    }
  }
}

</style>