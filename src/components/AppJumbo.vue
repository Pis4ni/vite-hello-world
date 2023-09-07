<script>
export default {
    data() {
        return {
            image:"47tv.gif"
        }
    },
    methods:{
        buildImgPath(imgName){
            const imgUrl = new URL('../assets/img/' + imgName, import.meta.url);
            return imgUrl.href
        }
    }
}
</script>

<template>
    <div>
        <h2> Jumbo Component </h2>
        <img :src="buildImgPath(image)" alt="">
    </div>
</template>

<style lang="scss" scoped>
div{
    width: 500px;
    img {
        width: 100%;
    }
}
</style>
