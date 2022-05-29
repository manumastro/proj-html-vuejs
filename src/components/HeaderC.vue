<template>
  <header>
    <div class="container d-flex h-100">
      <div class="logo h-100 d-flex align-items-center justify-content-center">
        <a href="#">
          <img src="../assets/images/logo.png" alt="THE KEYNOTE">
        </a>
      </div>
      <nav class="navbar w-100 mt-1">
        <ul class="d-flex align-items-center m-0">
          <li><a class="active" href="#wrapper-jumbo">home</a></li>
          <li><a href="#">pages</a></li>
          <li><a href="#">program</a></li>
          <li><a href="#">tickets</a></li>
          <li><a href="#">speakers</a></li>
          <li><a href="#">papers</a></li>
          <li><a href="#">blog</a></li>
          <li><a href="#">shortcodes</a></li>
          <li class="pe-4" id="line">|</li>
          <li><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a></li>    
        </ul>    
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderC'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';

header{
  height: 110px;
  background-color: $white;
  .container{
    .logo{
      padding: 0 90px;
    }
  
    nav{
      ul{
        padding: 0 35px;
      }
      li{
        padding-right: 40px;
        &#line{
          font-size: 12px;
        }
      }
      a{
        position: relative;
        letter-spacing: 1px;
        color: $gray;
        text-transform: uppercase;
        font-size: 11px;
        font-weight: 700;
        &.active{
          color: $scarlet;
        }
        &.active::before{
          content: '';
          position: absolute;
          bottom: -10px;
          right: 0;
          height: 3px;
          width: 100%;
          background-color: $scarlet;
        }
      }
      
    }
  }
}
</style>