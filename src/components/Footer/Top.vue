<template>
  <div class="sfondo">
    <div class="container">
      <div class="box" v-for="(link, index) in links" :key="index">
        <img :src="require(`../../assets/img/${link.img}`)" :alt="link.span">
        <span>{{link.span}}</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "Top",
    data(){
      return{
        links: [
          {
            "img": "buy-comics-digital-comics.png",
            "span": "digital comics",
          },
          {
            "img": "buy-comics-merchandise.png",
            "span": "digital comics",
          },
          {
            "img": "buy-comics-subscriptions.png",
            "span": "digital comics",
          },
          {
            "img": "buy-comics-shop-locator.png",
            "span": "digital comics",
          },
          {
            "img": "buy-dc-power-visa.svg",
            "span": "digital comics",
          },
        ]
      }
    }
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

    &:last-child{
      img{
        height: 40px;
      }
    }

    img{
      height: 50px;

    }
    

    span{
      color: $colorwhite;
      padding: 10px;
      text-transform: $uppercase;
      font-size: 15px;
    }
  }

  
</style>