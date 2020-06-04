<template>
  <div class="pricing">

    <div class="pricing-slider">

      <label class="form-slider">

        <span>How Many User Do You Have</span>
        <input type="range" />
      </label>
        <div class="pricing-slider-value"></div>
    </div>

    <div class="pricing-items">

      <div class="pricing-item">

        <div class="pricing-item-inner">

          <div class="pricing-item-content">

            <div class="pricing-item-header">

              <div class="pricing-item-title">Basic</div>
              <div class="pricing-item-price">

                <span class="pricing-item-price-currency">$</span>
                <span class="pricing-item-price-ammount">13</span>
                <span class="pricing-item-price-after">/m</span>

              </div>

            </div>

          </div>

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
