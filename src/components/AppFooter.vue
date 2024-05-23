<script>

export default {
    data() {
        return {
            menuFootBar: [
                {
                    img: `/img/buy-comics-digital-comics.png`,
                    txt: `digital comics`,
                },
                {
                    img: `/img/buy-comics-merchandise.png`,
                    txt: `dc merchandise`,
                },
                {
                    img: `/img/buy-comics-subscriptions.png`,
                    txt: `subscription`,
                },
                {
                    img: `/img/buy-comics-shop-locator.png`,
                    txt: `comic shop locator`,
                },
                {
                    img: `/img/buy-dc-power-visa.svg`,
                    txt: `dc power visa`,
                },

            ],

            menuFootJumbo1: [
                {
                    title: true,
                    txt: `dc comics`,
                },
                {
                    title: false,
                    txt: `Characters`,
                },
                {
                    title: false,
                    txt: `Movies`,
                },
                {
                    title: false,
                    txt: `Tv`,
                },
                {
                    title: false,
                    txt: `Games`,
                },
                {
                    title: false,
                    txt: `Videos`,
                },
                {
                    title: false,
                    txt: `News`,
                },
                {
                    title: true,
                    txt: `shop`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },

            ],

            menuFootJumbo2: [
                {
                    title: true,
                    txt: `dc`,
                },
                {
                    title: false,
                    txt: `Characters`,
                },
                {
                    title: false,
                    txt: `Movies`,
                },
                {
                    title: false,
                    txt: `Tv`,
                },
                {
                    title: false,
                    txt: `Games`,
                },
                {
                    title: false,
                    txt: `Videos`,
                },
                {
                    title: false,
                    txt: `News`,
                },
                {
                    title: false,
                    txt: `shop`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },
                {
                    title: false,
                    txt: `dc merchandise`,
                },

            ],

            menuFootJumbo3: [
                {
                    title: true,
                    txt: `sites`,
                },
                {
                    title: false,
                    txt: `DC`,
                },
                {
                    title: false,
                    txt: `MAD Magazine`,
                },
                {
                    title: false,
                    txt: `DC Kids`,
                },
                {
                    title: false,
                    txt: `DC Universe`,
                },
                {
                    title: false,
                    txt: `DC Power Visa`,
                },
            ],
        }
    }
}

</script>

<template>
    <footer>
        <div class="d-flex boxed align-items-center justify-content-around text-center h-100">
            <div v-for="elemento in menuFootBar" class="me-3 ms-3 col-2">
                <img :src="elemento.img" alt="" class="me-2 ms-2 my-img-w">
                {{ elemento.txt }}
            </div>
        </div>

        <div class="my-foot-jumbo">
            <div class="boxed d-flex">
                <div class="my-col-w d-flex align-items-left flex-column flex-wrap">
                    <div class="col-3 p-5">
                        <div v-for=" elemento in menuFootJumbo1">{{ elemento.txt }}</div>
                    </div>
                    <div class="col-3 p-5">
                        <div v-for=" elemento in menuFootJumbo2">{{ elemento.txt }}</div>
                    </div>
                    <div class="col-3 p-5">
                        <div v-for=" elemento in menuFootJumbo3">{{ elemento.txt }}</div>
                    </div>
                </div>
                <div class="my-col-bg my-col-w"></div>
            </div>
        </div>

        <div class="my-foot-end">
            <div class="boxed d-flex">
                <div class="col-6 my-foot-h d-flex align-items-center"><button type="button"
                        class="btn btn-outline-primary">SIGN-UP NOW!</button>
                </div>
                <div class="col-6 d-flex  align-items-center justify-content-center">
                    <div class="">FOLLOW US</div>
                    <img src="/img/footer-facebook.png" alt="">
                    <img src="/img/footer-twitter.png" alt="">
                    <img src="/img/footer-youtube.png" alt="">
                    <img src="/img/footer-pinterest.png" alt="">
                    <img src="/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    background-color: #0282f9;
    height: 9rem;
}

.my-foot-jumbo {
    background-image: url(/img/footer-bg.jpg);
    background-size: cover;
    height: 23rem;
}

.my-col-bg {
    background-image: url(/img/dc-logo-bg.png);
    background-size: 80%;
    background-repeat: no-repeat;
    background-position: center;
    margin-left: 1rem;
    z-index: 999;
    width: 100%;
}

.my-col-w {
    width: 50%;
    height: 368px;
}

.my-foot-end {
    background-color: #303030;
    height: 7rem;
}

.my-foot-h {
    height: 7rem;
}
</style>