<template>
  <div class="product-card">
    <div class="product-image">
      <router-link to="/jj">
        <img
          :src=" image ? image : 'https://images.unsplash.com/photo-1495105787522-5334e3ffa0ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80'"
          alt="img"
        />
      </router-link>
    </div>

    <div class="product-description">
      <h3>Great Jacket</h3>
      <p
        class="description"
      >Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam, eius.</p>
      <div class="card-footer">
        <p class="price">$500</p>
        <button class="btn-primary">Add to cart</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    price: {
      type: Number
    },
    image: {
      type: String
    }
  }
}
</script>

<style lang="scss" scoped>
@import './product-card.styles.scss';
</style>
