<template>
  <section>
    <div class="container wrapper">
    <h3>RECENT NEWS</h3>
    <div class="cards d-flex justify-content-between">
      <div class="news-card">
        <img src="../assets/images/photodune-7770665-two-white-coffee-mug-with-diy-decoration-o.jpg" alt="">
        <div class="date-comments">
          <span class="date">03 Dec 2013</span>
          <span class="comments-amount">0 Comments</span>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, doloribus. Doloremque labore repellat itaque, reprehenderit laboriosam deleniti explicabo. Fugit obcaecati excepturi doloribus expedita veritatis eligendi nam accusantium ea odio molestias!
        </p>
        <a href="#">Read More</a>
      </div>
      <div class="news-card">
        <img src="../assets/images/photodune-7770665-two-white-coffee-mug-with-diy-decoration-o.jpg" alt="">
        <div class="date-comments">
          <span class="date">03 Dec 2013</span>
          <span class="comments-amount">0 Comments</span>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, doloribus. Doloremque labore repellat itaque, reprehenderit laboriosam deleniti explicabo. Fugit obcaecati excepturi doloribus expedita veritatis eligendi nam accusantium ea odio molestias!
        </p>
        <a href="#">Read More</a>
      </div>
      <div class="news-card">
        <img src="../assets/images/photodune-7770665-two-white-coffee-mug-with-diy-decoration-o.jpg" alt="">
        <div class="date-comments">
          <span class="date">03 Dec 2013</span>
          <span class="comments-amount">0 Comments</span>
        </div>
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
section{
  padding: 90px 0;
  .wrapper{
    padding: 0 100px;
    h3{
      font-weight: 600;
      padding-bottom: 20px;
    }
    .news-card{
      width: 31.5%;
      img{
        width: 100%;
      }
    }
  }
}
</style>