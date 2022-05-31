<template>
  <section>
    <div class="container wrapper d-flex">
      <div id="presentation">
        <h1>PRESENTATION</h1>
        <img src="../assets/images/461365506_640.jpg" alt="">
      </div>
      <div id="twitter-feed">
        <h1>TWITTER FEED</h1>

        <div class="tweet">
          <div class="d-flex">
            <i class="fa-brands fa-twitter pe-3"></i>
            <p class="tweet-text mb-2">
            Stand out and be vibrant with some of the best bright and bold templates on Envato Elements. And add a splash of c.. <a href="#">https://t.co/jFrsnzEJK7 </a> 
            </p>
          </div>
          <span class="days-ago">3 days ago</span>
        </div>   

        <div class="tweet">
          <div class="d-flex">
            <i class="fa-brands fa-twitter pe-3"></i>
            <p class="tweet-text mb-2">
            Stand out and be vibrant with some of the best bright and bold templates on Envato Elements. And add a splash of c.. <a href="#">https://t.co/jFrsnzEJK7 </a> 
            </p>
          </div>
          <span class="days-ago">3 days ago</span>
        </div> 

        <div class="tweet">
          <div class="d-flex">
            <i class="fa-brands fa-twitter pe-3"></i>
            <p class="tweet-text mb-2">
            Stand out and be vibrant with some of the best bright and bold templates on Envato Elements. And add a splash of c.. <a href="#">https://t.co/jFrsnzEJK7 </a> 
            </p>
          </div>
          <span class="days-ago">3 days ago</span>
        </div>    

      </div>
    </div>
  </section>
</template>

<script>
export default {
name: 'PresentationTwitterFeed'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss'; 
section{
  padding: 80px 0;
  .wrapper{
    padding: 0 100px;
    #presentation{
      width: 50%;
      h1{
        font-size: 25px;
        font-weight: 600;
        letter-spacing: 3px;
      }
      img{
        margin: 25px 0 0 40px;
        width: 80%;
      }
    }
    #twitter-feed{
      width: 50%;
      .tweet{
        margin-bottom: 27px;
      }
      h1{
        font-size: 25px;
        font-weight: 600;
        letter-spacing: 3px;
        margin-bottom: 35px;
      }
      i{
        color: #47bdee;
        font-size: 24px;
      }
      p{
        color: $gray;
        font-size: 13px;
        letter-spacing: 0.5px;
        a{
          color: $scarlet;
        }
      }
      span.days-ago{
        margin-left: 40px;
        font-style: italic;
        font-size: 12px;
        color: $gray;

      } 
    }
  }
}
</style>