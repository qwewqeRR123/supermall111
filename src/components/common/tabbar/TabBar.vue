<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>

import cart from '../../../views/cart/cart.vue'
import category from '../../../views/category/category.vue'
import home from '../../../views/home/home.vue'
import profile from '../../../views/profile/profile.vue'

export default {
  name: 'TabBar',
  components: {
    cart,
    category,
    home,
    profile
  }
}
</script>

<style scoped>
#tab-bar {
  display: flex;
  background-color: #f6f6f6;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow: 0 -3px 10px rgba(0, 0, 0, .2);
}
</style>