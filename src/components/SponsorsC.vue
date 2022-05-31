<template>
  <section>
    <div class="container wrapper">
      <div id="head" class="text-center">
        <h1>SPONSORS</h1>
        <span>Maecenas faucibus mollis interdum. Nullam id dolor <br> id nibh ultricies vehicula ut id elit.</span>
      </div>
      <div id="sponsors" class="d-flex justify-content-between">
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-1.jpg" alt=""></a></div>
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-2.jpg" alt=""></a></div>
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-3.jpg" alt=""></a></div>
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-4.jpg" alt=""></a></div>
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-5.jpg" alt=""></a></div>
        <div class="sponsor"><a href="#"><img src="../assets/images/banner-6.jpg" alt=""></a></div>
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
  background-color: #f6f6f6;
  padding: 80px 0 60px 0;
  .wrapper{
    padding: 0 100px;
    #head{
      margin-bottom: 55px;
      h1{
      letter-spacing: 3px;
      font-weight: bold;
      margin-bottom: 17px;
      }
      span{
        color: $gray;
        font-size: 15px;
      }
    }
  }
}
</style>