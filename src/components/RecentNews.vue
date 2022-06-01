<template>
  <section>
    <div class="container wrapper">
    <h3>RECENT NEWS</h3>
    <div class="cards d-flex justify-content-between">
      <div class="news-card">
        <img src="../assets/images/photodune-7770665-two-white-coffee-mug-with-diy-decoration-o.jpg" alt="">
        <div class="sticky-post">
          <i class="fa-solid fa-bullhorn pe-2"></i>
          <span>STICKY POST</span>
        </div>
        <div class="date-comments">
          <span class="date pe-3">03 Dec 2013</span>
          <span class="pe-3">/</span>
          <span class="comments-amount">0 Comments</span>
        </div>
        <h5>SEDIAL EIUSMOD TEMPOR</h5>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, doloribus. Doloremque labore repellat itaque, reprehenderit laboriosam deleniti explicabo. Fugit obcaecati excepturi doloribus expedita veritatis eligendi nam accusantium ea odio molestias!
        </p>
        <a href="#">Read More</a>
      </div>
      <div class="news-card">
        <img src="../assets/images/photodune-8797753-multiethnic-people-with-startup-business-t.jpg" alt="">
        <div class="sticky-post">
          <i class="fa-solid fa-bullhorn pe-2"></i>
          <span>STICKY POST</span>
        </div>
        <div class="date-comments">
          <span class="date pe-3">03 Dec 2013</span>
          <span class="pe-3">/</span>
          <span class="comments-amount">2 Comments</span>
        </div>
        <h5>DONEC LUCTUS IMPERDIET</h5>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, doloribus. Doloremque labore repellat itaque, reprehenderit laboriosam deleniti explicabo. Fugit obcaecati excepturi doloribus expedita veritatis eligendi nam accusantium ea odio molestias!
        </p>
        <a href="#">Read More</a>
      </div>
      <div class="news-card">
        <img src="../assets/images/photodune-8522811-speaker-at-business-conference-and-present.jpg" alt="">
        <div class="sticky-post">
          <i class="fa-solid fa-bullhorn pe-2"></i>
          <span>STICKY POST</span>
        </div>
        <div class="date-comments">
          <span class="date pe-3">03 Dec 2013</span>
          <span class="pe-3">/</span>
          <span class="comments-amount">2 Comments</span>
        </div>
        <h5>MAGNA PARS STUDIORUM</h5>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, doloribus. Doloremque labore repellat itaque, reprehenderit laboriosam deleniti explicabo. Fugit obcaecati excepturi doloribus expedita veritatis eligendi nam accusantium ea odio molestias!
        </p>
        <a href="#">Read More</a>
      </div>

    </div>
    </div>
  </section>
</template>

<script>
export default {
name: 'RecentNews'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  padding: 80px 0;
  .wrapper{
    padding: 0 100px;
    h3{
      font-weight: 600;
      font-size: 26px;
      letter-spacing: 2px;
      padding-bottom: 20px;
      margin-bottom: 30px;
    }
    .news-card{
      position: relative;
      width: 31.5%;
      &:hover .sticky-post{

        opacity: 1;
      }
      img{
        width: 100%;
        margin-bottom: 25px;
      }
      .sticky-post{
        position: absolute;
        top: 169px;
        right: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 6px 5px;
        width: 40%;
        background-color: #232323;
        color: white;
        opacity: 0;
        transition: all 0.3s ease-in-out;
        span, i{
          font-weight: bold;
          font-size: 14px;
        }
      }
      .date-comments{
        font-style: italic;
        color: $gray;
        margin-bottom: 6px;
      }
      h5{
        font-weight: bold;
        margin-bottom: 20px;
      }
      p{
        color: $gray;
        font-size: 13px;
      }
      a{
        color: $scarlet;
        font-style: italic;
      }
    }
  }
}
</style>