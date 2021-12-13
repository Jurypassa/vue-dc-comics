<template>
  <div class="sfondo">
      <div class="container">
          <div class="box1">
            <h2>dc comics</h2>
            <ul>
              <li>Characters</li>
              <li>Comisc</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>

            <h2>shop</h2>
            <ul>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>

            <h2>dc</h2>
            <ul>
              <li>Terms Of Use</li>
              <li>Privicy police (New)</li>
              <li>Ad Choises</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshops</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Helps</li>
              <li>Contact US</li>
            </ul>

            <h2>sites</h2>
            <ul>
              <li>DC</li>
              <li>Mad MAgazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
          </div>
          <div class="box2">
            
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Middle"
}
</script>

<style scoped lang="scss">
@import "../../assets/style/partials/variable.scss";

  .sfondo{
    background-image: url(../../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
  }

  .container{
    display: flex;
    justify-content: space-between;

    .box1{
      display: flex;
      flex-direction: column;
      flex-wrap: wrap;
      width: 30%;
      max-height: 350px;
      margin: 40px 0;

      h2{
        color: $colorwhite;
        text-transform: $uppercase;
        font-size: 18px;
        padding: 20px 0;
      }

      li{
        color: $colorgray;
        font-size: 11px;
        font-weight: bold;
        list-style: none;
        padding: 4px;
      }
    }

    .box2{
      width: 50%;
      background-image: url(../../assets/img/dc-logo-bg.png);
      background-size:100%;
      background-repeat: no-repeat;
      background-position: right;
    }
  }

  
</style>