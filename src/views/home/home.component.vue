<template>
  <main>
    <section class="hero">
      <img
        src="https://img-b.udemycdn.com/notices/featured_banner/image_udlite/d929f8d4-28f6-42c8-aa69-fd6ba05951b9.jpg"
        alt="img"
      />
      <div class="box-title">
        <h1>Shopping never stops — but offers do</h1>
        <p>It's the last day to get courses from Rp172,900</p>
      </div>
    </section>
    <Wishlist />
    <PopularProduct />
  </main>
</template>

<script>
import Wishlist from '../../components/wishlist/wishlist.component'
import PopularProduct from '../../components/popular-product/popular-product.component'

export default {
  components: {
    Wishlist,
    PopularProduct
  }
}
</script>

<style lang="scss" scoped>
@import './home.styles.scss';
</style>
