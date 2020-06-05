<template>
  <div class="cart-item">
    <div class="item-image">
      <img :src="image" alt="img" />
    </div>
    <div class="item-description">
      <h3>{{ name }}</h3>
      <p>Lorem ipsum dolor sit amet.</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    image: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
@import './cart-dropdown-item.styles.scss';
</style>
