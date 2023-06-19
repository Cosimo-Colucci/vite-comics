<template>
    <div>
        <img :src="imgURL" alt="">
    </div>
</template>

<script>
    export default {
        name: 'CardMain',
        props: {
            imgURL: URL
        }
    }
</script>

<style>

</style>