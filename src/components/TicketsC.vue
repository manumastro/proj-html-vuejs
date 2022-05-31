<template>
  <section id="tickets">
    <h1 class="text-center">TICKETS</h1>
    <div class="container wrapper d-flex align-items-center justify-content-between">

      <div class="ticket-card">
        <div class="top d-flex flex-column">
          <span class="days">ONE DAY PASS</span>
          <span class="price">FREE</span>
        </div>
        <div class="middle d-flex align-items-center flex-column">
          <span class="pb-3">One Day Access</span>
          <span class="pb-3">Coffee Break</span>
          <span class="pb-3">Lunch(International Buffet)</span>
          <span class="pb-3">Document Sheets</span>
          <span>50USD Voucher For Next Event</span>
        </div>
        <div class="bottom text-center">
          <a href="#">BOOK NOW</a>
        </div>
      </div>
      <div class="ticket-card">
        <div class="top d-flex flex-column">
          <span class="days">FOUR DAY PASSES</span>
          <span class="price">750.00 USD</span>
        </div>
        <div class="middle d-flex align-items-center flex-column">
          <span class="pb-3">Four Day Access</span>
          <span class="pb-3">Coffee Break</span>
          <span class="pb-3">Lunch(International Buffet)</span>
          <span class="pb-3">Document Sheets</span>
          <span>100USD Voucher For Next Event</span>
        </div>
        <div class="bottom text-center">
          <a href="#">BOOK NOW</a>
        </div>
      </div>
      <div class="ticket-card">
        <div class="top d-flex flex-column">
          <span class="days">TWO DAY PASSES</span>
          <span class="price">580.00 USD</span>
        </div>
        <div class="middle d-flex align-items-center flex-column">
          <span class="pb-3">Two Day Access</span>
          <span class="pb-3">Coffee Break</span>
          <span class="pb-3">Lunch(International Buffet)</span>
          <span class="pb-3">Document Sheets</span>
          <span>70USD Voucher For Next Event</span>
        </div>
        <div class="bottom text-center">
          <a href="#">BOOK NOW</a>
        </div>
      </div>
      
      
    </div>
  </section>
</template>

<script>
export default {
name: 'TicketsC'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/_vars.scss';
section{
  padding: 80px 0;
  background-image: url('../assets/images/ticket-bg.jpg');
  background-position: center;
  h1{
    color: #f9f9f9;
    font-weight: 600;
    font-size: 38px;
    letter-spacing: 2px;
    margin-bottom: 50px;
  }
  .wrapper{
    padding: 0 100px;
    .ticket-card{
      width: 31.5%;
      .top{
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px 0;
        background-color: #e9e9e9;
        .days{
          font-size: 20px;
          font-weight: 600;
        }
        .price{
          font-weight: 600;
          color: $scarlet;
        }
      }
      .middle{
        padding: 32px 0;
        background-color: #f9f9f9;
        span{
          font-size: 15px;
          font-style: italic;
          color: $gray;
        }
      }
      .bottom{
        padding: 15px 0;
        background-color: $scarlet;
        a{
          color: #f9f9f9;
          font-weight: 600;
          font-size: 14px;
        }
      }
    }
  }
}
</style>