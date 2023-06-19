<template>
    <main>
        <div class="contents">
            <p>- - - Content goes here - - -</p>
        </div>
        <CardMain/>
    </main>
</template>

<script>
import CardMain from '../components/CardMain.vue';

export default {
    name: 'MainApp',
    components: {
        CardMain,
    },
    data(){
        return{
            listData:[
                {
                "imgURL": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                "price": "$19.99",
                "series": "Action Comics",
                "type": "comic book",
                },
            ]
        }
    }
}
</script>

<!-- lang="scss" -->
<style scoped>
main{
    background-color: black;
    color: white;
}
div.contents p{
    padding: 2rem;
} 
</style>