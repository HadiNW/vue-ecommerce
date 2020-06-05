<template>
  <section class="popular-product">
    <h2>Popular Products</h2>
    <h3>Find the best offers !</h3>
    <div class="popular-products">
      <ProductCard image="https://images.pexels.com/photos/298864/pexels-photo-298864.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" />
      <ProductCard />
      <ProductCard image="https://images.pexels.com/photos/298864/pexels-photo-298864.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" />
      <ProductCard />
      <ProductCard />
      <ProductCard />
      <ProductCard image="https://images.pexels.com/photos/298864/pexels-photo-298864.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" />
      <ProductCard image="https://images.pexels.com/photos/994517/pexels-photo-994517.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" />
      <ProductCard image="https://images.pexels.com/photos/2205839/pexels-photo-2205839.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" />
    </div>
  </section>
</template>

<script>
import ProductCard from '../product-card/product-card.component'

export default {
  components: {
    ProductCard
  }
}
</script>

<style lang="scss" scoped>
@import './popular-product.styles.scss';
</style>
