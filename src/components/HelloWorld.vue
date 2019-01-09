<template>
  <div class="c-widget">
    <div class="widget-admin">
      <div class="widget-admin_view">
        <label>
          <input type="radio" name="w-view" checked>
          <span>Вид 1</span>
        </label>
        <label>
          <input type="radio" name="w-view">
          <span>Вид 2</span>
        </label>
        <label>
          <input type="radio" name="w-view">
          <span>Вид 3</span>
        </label>
      </div>
    </div>

    <div class="widget">
      <div class="car">
        <div class="car_photo">
          <img src="https://rentride.ru/upload/resize_cache/iblock/656/300_180_0/65619a018c8f0ae8a972de98de0da585.jpg" alt="2007, Ford Fusion">
        </div>
        <div class="car_name">2007, Ford Fusion</div>
        <div class="car_option">опции</div>
        <div class="car_price">
          <span class="car_price-old">3000</span>
          <span class="car_price-current">1000</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
