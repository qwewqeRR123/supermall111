<template>
  <div class="nav-bar-item">
    <div class="nav-bar-item1"></div>
    <div class="nav-bar-item2">购物街</div>
    <div class="nav-bar-item3"></div>
  </div>
</template>
<script>

export default {
  name: 'NavBarItem'
}
</script>

<style scoped>
.nav-bar-item1 {
  flex: 20%;
  height: 200px;
  background-color: green;
}
.nav-bar-item2 {
  flex: 60%;
  height: 200px;
  background-color: green;
}
.nav-bar-item3 {
  flex: 20%;
  height: 200px;
  background-color: green;
}
</style>