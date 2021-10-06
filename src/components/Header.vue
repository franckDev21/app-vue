<template>
  <header class="header">
    <div class="header_top">
      <div class="header__logo">@success_dev</div>
      <div class="widget"></div>
    </div>
    <div class="header_bottom">
      <div class="header__nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
      <div class="header__network"></div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
}
</script>

<style lang="scss">
  .header{
    padding: 15px 10px;
    background-color: #1e1f1e;
    color: #fff;
    &__top,&__bottom{
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    a.router-link-exact-active {
      color: #42b983;
    }
  }
</style>