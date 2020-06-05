<template>
  <div class="header">
    <div class="header-content">
      <div class="logo">
        <router-link tag="a" to="/">Logo</router-link>
      </div>
      <div class="search">
        <input placeholder="Search for anything" type="text" />
      </div>
      <nav>
        <ul>
          <li>
            <img class="icon cart-icon" :src="require('../../assets/icons/heart.svg')" alt="cart" />
          </li>
          <li>
            <div class="cart-icon-container">
              <p>5</p>
              <img class="icon cart-icon" :src="require('../../assets/icons/cart.svg')" alt="cart" />
            </div>
          </li>
          <li>
            <router-link class="btn-primary" to="/signin">Sign In</router-link>
          </li>
          <li><p class="account">HW</p></li>
        </ul>
      </nav>
    </div>
    <div class="sub-header">
      <ul>
        <router-link tag="li" to="/products/hats">
          <a>Hats</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Shoes</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Jackest</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Blouses</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Shirts</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Pants</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Blankets</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Sun Glasses</a>
        </router-link>
        <router-link tag="li" to="/products/hats">
          <a>Pillows</a>
        </router-link>
      </ul>
    </div>
    <CartDropdown />
  </div>
</template>

<script>
import CartDropdown from '../cart-dwopdown/cart-dropdown.component'

export default {
  components: {
    CartDropdown
  }
}
</script>
<style lang="scss" scoped>
@import './header.styles.scss';
</style>
