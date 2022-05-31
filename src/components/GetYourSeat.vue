<template>
  <div id="get-your-seat" class="item d-flex flex-column">
          <h5>{{getYourSeat.title}}</h5>
          <p>{{getYourSeat.description}}</p>
          <button class="btn btn-danger"><a href="#">CHECK OUT TICKETS!</a></button>
        </div>
</template>

<script>
export default {
name: 'GetYourSeat',
props: {
  getYourSeat: Object
}
}
</script>

<style>

</style>