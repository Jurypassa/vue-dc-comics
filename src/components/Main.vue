<template>
  <div class="sfondo">
      <div class="jumbo">
          <img src="../assets/img/jumbotron.jpg" alt="">
      </div>
      <div class="titolo">
          <h2>current series</h2>
      </div>
      <Card/>
      <div class="load">
          <h4>load more</h4>
      </div>
  </div>
</template>

<script>
import Card from './Card/Card.vue'
export default {
    name: "Main",
    components: {
    Card
  }
}
</script>


<style scoped lang="scss">
@import "../assets/style/partials/variable.scss";
@import "../assets/style/partials/mixins.scss";

    .sfondo{
        position: relative;
        background-color: #1c1c1c;

        img{
            width: 100%;
            height: 400px;
            object-fit: cover;
            object-position: top;
            display: block;
        }

    
        .titolo{
            @include corniceblu;
            position: absolute;
            left: 300px;
            top: 400px;
            transform: translate(0, -50%) ;
            z-index: 1;
        }

        .load{
            text-align: center;
            padding-bottom: 20px;
            h4{
                @include corniceblu;
                display: inline-block;
            }
            
        }
    }
    
</style>