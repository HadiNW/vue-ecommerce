<template>
  <section class="wishlist">
    <h2>Your Wishlist</h2>
    <h3>Recommended for you</h3>
    <div class="wishlist-products">
      <ProductCard />
      <ProductCard />
      <ProductCard />
      <ProductCard />
    </div>
  </section>
</template>

<script>
import ProductCard from '../../components/product-card/product-card.component'

export default {
  components: {
    ProductCard
  }
}
</script>

<style lang="scss" scoped>
@import './wishlist.styles.scss';
</style>
