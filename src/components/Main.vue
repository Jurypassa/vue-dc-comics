<template>
  <div class="sfondo">
      <div class="jumbo">
          <img src="../assets/img/jumbotron.jpg" alt="">
      </div>
      <Card/>
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


    img{
            width: 100vw;
            height: 400px;
            object-fit: cover;
            object-position: top;
            display: block;
        }

    p{
        color: white;
        font-size: 20px;
        font-weight: bold;

    }
</style>