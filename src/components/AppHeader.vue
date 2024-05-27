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
    <header class="d-flex">
        <div class="col-5 d-flex align-items-center justify-content-center"><img class="my-logo-w"
                src="/img/dc-logo.png" alt=""></div>
        <div class="col-7 d-flex align-items-center justify-content-start">
            <div v-for="item in menuHead" class="m-3">{{ item.toUpperCase() }}</div>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: white;
    color: black;
    height: 7rem;
}

.my-logo-w {
    width: 10%;
}
</style>