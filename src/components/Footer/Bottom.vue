<template>
  <div class="sfondo">
      <div class="container">
          <div>
              <button>sign-up now!</button>
          </div>
          
          <div>
              <span>follow us</span>
              <img src="../../assets/img/footer-facebook.png" alt="logo facebook">
              <img src="../../assets/img/footer-twitter.png" alt="logo facebook">
              <img src="../../assets/img/footer-youtube.png" alt="logo facebook">
              <img src="../../assets/img/footer-pinterest.png" alt="logo facebook">
              <img src="../../assets/img/footer-periscope.png" alt="logo facebook">
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Bottom"
}
</script>

<style scoped lang="scss">
@import "../../assets/style/partials/variable.scss";

    .sfondo{
        background-color: #303030;
    }

    .container{
        height: 110px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        div:nth-child(2){
            display: flex;
            align-items: center;

            span{
                color: $colorblue;
                font-size: 17px;
                font-weight: bold;
                text-transform: $uppercase;
                padding-right: 10px;
            }

            img{
                padding: 0 10px;
            }
        }
    }

    button{
        background-color: #303030;
        color: $colorwhite;
        border: 2px solid $colorblue;
        padding: 10px;
        text-transform: $uppercase;
        font-weight: bold;
        font-size: 15px;
    }
</style>