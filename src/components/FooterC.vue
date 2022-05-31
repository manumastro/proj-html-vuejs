<template>
  <footer>
    <section id="top">
      <div class="d-flex justify-content-between container wrapper">
        <AboutUs :aboutUs = aboutUs />
        <RecentNewsFooter :recentNews = recentNews />
        <GetYourSeat :getYourSeat = getYourSeat />
        <!-- <div id="gallery-from-last-year" class="item d-flex flex-column">
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
        </div> -->
        <GalleryFromLastYear :galleryFromLastYear = galleryFromLastYear />
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
import AboutUs from './AboutUs.vue'
import GalleryFromLastYear from './GalleryFromLastYear.vue'
import GetYourSeat from './GetYourSeat.vue'
import RecentNewsFooter from './RecentNewsFooter.vue'
export default {
  components: { AboutUs, RecentNewsFooter, GetYourSeat, GalleryFromLastYear },
name: 'FooterC',
data(){
  return{
    aboutUs: {
      title: 'ABOUT US',
      description: 'Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.',
      icons: {
        facebook: 'fa-brands fa-facebook-square',
        twitter: 'fa-brands fa-twitter-square',
        linkedin: 'fa-brands fa-linkedin',
        googlePlus: 'fa-brands fa-google-plus-square',
        pinterest: 'fa-brands fa-pinterest-square',
      }
    },
    recentNews: {
      title: 'RECENT NEWS',
      links: [
        'SEM PORTA MOLLIS PARTURIENT',
        'NULLAM LOREM MATTIS PURUS',
        'NIBH SEM SIT ULLAMCORPER',
        'DONEC LUCTUS IMPERDIET',
        'MAGNA PARS STUDIORUM'
      ]
    },
    getYourSeat: {
      title: 'GET YOUR SEAT!',
      description: 'Book for your seat before its too rate. We provide variety of ticket options.',
      button: 'CHECK OUT TICKETS!'
    },
    galleryFromLastYear: {
      title: 'GALLERY FROM LAST YEAR',
      images: [
        '6426608875_186070f8ca_o-150x150.jpg',
        'photodune-8523683-speaker-at-business-convention-and-present.jpg',
        'photodune-6745579-modern-creative-man-relaxing-on-workspace-.jpg',
        'photodune-8522811-speaker-at-business-conference-and-present (1).jpg',
        'photodune-8797753-multiethnic-people-with-startup-business-t (1).jpg',
        'card04-150x150.jpg',
        'photodune-8797753-multiethnic-people-with-startup-business-t (1).jpg',
        'photodune-6745585-modern-creative-workspace-m-150x150.jpg',
        '6426608875_186070f8ca_o-150x150.jpg',
        'card01-150x150.jpg',
        '13349065283_64d09b067c_o-150x150.jpg',
        'photodune-8795110-overhead-of-essentials-denim-clothes-m-150.jpg',
      ]
    }
  }
}
}
</script>

<style lang="scss">
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
      
        img{
          width: calc((100% / 4) - 8px);
          padding-bottom: 10px;
      
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