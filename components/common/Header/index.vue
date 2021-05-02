<template>
  <header>
    <div class="wrap-main">
      <nuxt-link to="/home" class="logo">
        <i class="logo-img"></i>
      </nuxt-link>
    </div>
    <div class="clr"></div>
  </header>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
header {
  width: 100%;
  height: 80px;
  .wrap-main {
    width: 100%;
    height: 50%;
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;

    .logo {
      width: 170px;
      height: 100%;
      &-img {
        width: 156px;
        height: 30px;
        background-image: url("./img/icondesktop20200728@1x.png");
        background-position: 0 0;
        display: block;
      }
    }
  }
  .clr {
    width: 100%;
    height: 50%;
    background-color: #fed101;
  }
}
</style>
