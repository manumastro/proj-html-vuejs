<template>
  <section id="program">

    <div class="container wrapper">
      <div id="top" class="d-flex align-items-center justify-content-between">
        <div id="left" class="d-flex align-items-center">
          <h1 class="me-5">PROGRAM</h1>
          <p class="m-0">
            This conference run through all 4 days from 23 - 26 May 2016. <br>
            We also provide free lunch and coffee break in each day.
          </p>
        </div>
        <div id="right" class="d-flex align-items-center">
          <a href="#">View Full Program</a>
        </div>
      </div>

      <div id="bottom" class="d-flex flex-column">

        <div id="days" class="d-flex">
          <div class="day active">
            <span class="day-number">DAY 1</span>
            <span class="date">23 May 2016</span>
          </div>
          <div class="day">
            <span class="day-number">DAY 1</span>
            <span class="date">23 May 2016</span>
          </div>
          <div class="day">
            <span class="day-number">DAY 1</span>
            <span class="date">23 May 2016</span>
          </div>
          <div class="day">
            <span class="day-number">DAY 1</span>
            <span class="date">23 May 2016</span>
          </div>
          <div class="day">
            <span class="day-number">DAY 1</span>
            <span class="date">23 May 2016</span>
          </div>
        </div> 

        <div class="d-flex conference-infos">
          <div class="d-flex flex-column left">
            <div class="hour d-flex align-items-center mb-3">
              <i class="fa-solid fa-clock me-2"></i>
              <p class="m-0">09:00 - 10:30</p>
            </div>
            <div class="room d-flex align-items-center mb-3">
              <i class="fa-solid fa-location-arrow me-2"></i>
              <p class="m-0">ROOM A</p>
            </div>
            <div class="speaker-name d-flex align-items-center">
              <i class="fa-solid fa-user me-2"></i>
              <p class="m-0">LAURENCE FRANCIS</p>
            </div>
          </div>
          <div class="d-flex flex-column right">
            <div class="introduction pb-3">
              <h5>WELCOMING AND INTRODUCTION</h5>
            </div>
            <div class="description pb-4">
              <p>
                Vestibulum id ligul porta felis eusimod semper. Nullam quis risus eget urna mollis ornare vel eu leo. Donec <br> ullamcorpoer nulla non metus auctor fringilla. Aenean lacinia bibendum nulla sed consectetur...
              </p>
            </div>
            <div class="speaker-image">
              <img src="../assets/images/speaker-8-150x150.jpg" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>

  </section>
</template>

<script>
export default {
name: 'ProgramC'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  padding: 100px 0 80px 0;
  .wrapper{
    padding: 0 100px;
    #top{
      margin-bottom: 60px;
      #left{
        h1{
          font-size: 35px;
          font-weight: bold;
          letter-spacing: 3px;
        }
        p{
          color: $gray;
          font-size: 0.9rem;
        }
      }
      #right a{
        font-style: italic;
        font-size: 0.9rem;
        color: $scarlet;
      }
    }
    #bottom{
      #days{
        background-color: $scarlet;
        .day{
          display: flex;
          flex-direction: column;
          padding: 10px 80px 10px 25px;
          color: $white;
          border-right: 0.1px solid rgba($color: $mine-shaft, $alpha: 0.6);
          cursor: pointer;
          &.active{
            background-color: #d3290f;
          }
          .day-number{
            font-size: 1.2rem;
            font-weight: bold;
          }
          .date{
            font-size: 0.85rem;
            font-weight: 500;
          }
        }
      }
      .conference-infos{
        background-color: #f7f7f7;
        padding: 60px 0 60px 45px;
        .left{
          margin-right: 150px;
          font-size: 0.80rem;
          color: $gray;
        }
        .right{
          .introduction h5{
            font-weight: 600;
            letter-spacing: 4px;
            color: $gray;
          }
          .description p{
            font-size: 0.9rem;
            color: $gray;
          }
          .speaker-image{
            width: 50px;
            height: 50px;
            img{
              width: 100%;
              border-radius: 4px;
            }
          }
        }
      }
    }
  }
}
</style>