<template>
    <header>
        <div class="logo_img">

        </div>
        <div class="navbar">

        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderApp',
    data(){
        return{

        }
    }
}
</script>

<!-- lang="scss" -->
<style scoped>
header{
    display: flex;
    justify-content: space-between;
    height: 250px;
}
div.logo_img {
    background-color: red;
    width: 10%;
}

div.navbar {
    background-color: red;
    width: 55%;
}

</style>