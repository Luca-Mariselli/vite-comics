<script>

export default {
    data() {
        return {
            menuHead: [
                `characters`,
                `comics`,
                `movies`,
                `tv`,
                `games`,
                `collectibles`,
                `videos`,
                `fans`,
                `news`,
                `shop`

            ]
        }
    }
}

</script>

<template>
    <header class="mt-3 d-flex">
        <div class="col-5 d-flex align-items-center justify-content-center">LOGO</div>
        <div class="col-7 d-flex align-items-center justify-content-start">
            <div v-for="item in menuHead" class="m-3">{{ item }}</div>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: white;
    color: black;
    height: 7rem;
}
</style>