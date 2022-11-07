<script>
export default {
    data() {
        return {
            imgName: `326271.png`
        }
    },
    methods: {
        getImagePath() {
            return new URL(`../assets/${this.imgName}`, import.meta.url).href;
        }
    }
}
</script>
<template>
    <div class="jumbo">
        <img :src="getImagePath()" alt="">
    </div>
</template>
<style scoped>
.jumbo {
    width: 100%;
    height: 60vh;
}

.jumbo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>