<script>

export default {
    props: [
        `fumetto`
    ],

    data() {
        return {

        }
    },

}

</script>

<template>


    <div class="col-2 mb-5">
        <div class="my-cards" :style="{ backgroundImage: 'url(' + fumetto.thumb + ')' }"></div>
        <div class="mt-4 font-medio">{{ fumetto.series.toUpperCase() }}</div>

    </div>


</template>

<style scoped>
.my-cards {
    width: 200px;
    height: 200px;
    background-size: cover;

}
</style>