<template>
  <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            
            <nav>
                <ul>
                    <li><a href="#">characters</a></li>
                    <li><a href="#">comics</a></li>
                    <li><a href="#">movies</a></li>
                    <li><a href="#">tv</a></li>
                    <li><a href="#">games</a></li>
                    <li><a href="#">collectibles</a></li>
                    <li><a href="#">videos</a></li>
                    <li><a href="#">fans</a></li>
                    <li><a href="#">news</a></li>
                    <li><a href="#">shop</a></li>
                </ul>   
            </nav>
            
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped lang="scss">
@import "../assets/style/partials/variable.scss";
    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 0;
    }

    nav{
        ul{
            display: flex;
            list-style: none;

            li a{
                padding: 60px 10px;
                text-decoration:none;
                text-transform: uppercase;
                color: $colorblack;
                font-weight:bold;
                font-size: 13px;
                &:hover{
                    color: $colorblue;
                    border-bottom: 3px solid $colorblue;

                }
            }
        }
    }
</style>