<template>
  <section class="container">
    <nuxt/>
    <product/>
    <my-footer/>
  </section>
</template>

<script>
import Product from '~components/Product.vue'
import MyFooter from '~components/Footer.vue'

export default {
  components: {
    Product,
    MyFooter
  }
}

</script>

<style>
.container{
  margin: 0;
  width: 100%;
  padding: 100px 0;
  text-align: center;
}

</style>
