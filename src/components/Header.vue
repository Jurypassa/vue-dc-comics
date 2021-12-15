<template>
  <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            
            <nav>
                <ul>
                    <li v-for="(link, index) in links" :key="index">
                        <a :href="link.href">{{link.section}}</a>
                    </li>
                </ul>   
            </nav>
            
        </div>
    </header>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            links: [
                {
                    "href": "#",
                    "section": "characters"
                },
                {
                    "href": "#",
                    "section": "comics"
                },
                {
                    "href": "#",
                    "section": "movies"
                },
                {
                    "href": "#",
                    "section": "tv"
                },
                {
                    "href": "#",
                    "section": "games"
                },
                {
                    "href": "#",
                    "section": "collectible"
                },
                {
                    "href": "#",
                    "section": "videos"
                },
                {
                    "href": "#",
                    "section": "fans"
                },
                {
                    "href": "#",
                    "section": "news"
                },
                {
                    "href": "#",
                    "section": "sjop"
                }
            ]
        }
    }
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
                padding: 62px 10px;
                text-decoration:none;
                text-transform: $uppercase;
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