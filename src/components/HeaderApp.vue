<template>
    <header>
        <div class="logo_img">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="navbar">
            <ul>
                <li v-for="obj in navbarList">
                    {{ obj }}
                </li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderApp',
    data(){
        return{
           navbarList:[
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Collectibles",
                "Videos",
                "Fans",
                "News",
                "Shop"            
           ]
        }
    }
}
</script>

<!-- lang="scss" -->
<style scoped>
header{
    display: flex;
    justify-content: space-between;
}
div.logo_img {
    background-color: red;
}

div.navbar {
    background-color: red;
    display: flex;
}

div.navbar ul{
    display: flex;
    list-style-type: none;
    margin: auto;
}

</style>