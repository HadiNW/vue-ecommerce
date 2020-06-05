<template>
  <div class="container">
    <div class="cart-dropdown">
      <CartDropdownItem
        name="Great Jakcet"
        image="https://images.unsplash.com/photo-1495105787522-5334e3ffa0ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
      />
      <CartDropdownItem
        name="Great Jakcet"
        image="https://images.unsplash.com/photo-1495105787522-5334e3ffa0ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
      />
      <CartDropdownItem
        name="Great Jakcet"
        image="https://images.unsplash.com/photo-1495105787522-5334e3ffa0ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
      />
      <CartDropdownItem
        name="Great Jakcet"
        image="https://images.unsplash.com/photo-1495105787522-5334e3ffa0ef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
      />
    </div>
   <div class="dropdown-footer">
       <p>Total Price : $170</p>
        <button class="btn-primary">Go to checkout</button>
   </div>
  </div>
</template>

<script>
import CartDropdownItem from '../cart-dropdown-item/cart-dropdown-item.component'

export default {
  components: {
    CartDropdownItem
  }
}
</script>

<style lang="scss" scoped>
@import './cart-dropdown.styles.scss';
</style>
