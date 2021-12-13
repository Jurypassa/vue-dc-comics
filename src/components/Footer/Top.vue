<template>
  <div class="sfondo">
      <div class="container">
          <div class="box">
            <img src="../../assets/img/buy-comics-digital-comics.png" alt="logo 1">
            <span>digital comics</span>
          </div>

          <div class="box">
            <img src="../../assets/img/buy-comics-merchandise.png" alt="logo 2">
            <span>dc merchandise</span>
          </div>

          <div class="box">
            <img src="../../assets/img/buy-comics-subscriptions.png" alt="logo 3">
            <span>subscription</span>
          </div>

          <div class="box">
            <img src="../../assets/img/buy-comics-shop-locator.png" alt="logo 4">
            <span>comic shop locator</span>
          </div>

          <div class="box">
            <img src="../../assets/img/buy-dc-power-visa.svg" alt="logo 5">
            <span>dc power visa</span>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Top"
}
</script>

<style scoped lang="scss">
@import "../../assets/style/partials/variable.scss";

  .sfondo{
    background-color: $colorblue;
  }

  .container{
    display: flex;
  }

  .box{
    padding: 30px;
    margin: 20px 0;
    display: flex;
    align-items: center;

    img{
      height: 45px;
    }

    span{
      color: $colorwhite;
      padding: 10px;
      text-transform: $uppercase;
      font-size: 15px;
    }
  }

  
</style>