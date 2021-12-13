<template>
  <div class="sfondo">
      <div class="container">
          <p> [Content goes here] </p>
      </div>
  </div>
</template>

<script>
export default {
    name: "Main"
}
</script>


<style scoped lang="scss">

    .sfondo{
        height: 150px;
        background-color: black;
        display: flex;
        align-items: center;
    }

    p{
        color: white;
        font-size: 20px;
        font-weight: bold;

    }
</style>