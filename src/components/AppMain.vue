<script>
export default {

}
</script>

<template>
    <main>
        <div class="container">
            <h3>Content goes here</h3>
        </div>
        <div class="container_down">
            <div class="row">
                <div class="col">
                    <img src="/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div class="col">
                    <img src="/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </div>
                <div class="col">
                    <img src="/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </div>
                <div class="col">
                    <img src="/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </div>
                <div class="col">
                    <img src="/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </div>
            </div>
        </div>
    </main>
</template>


<style scoped>
.container {
    background-color: var(--comics-dark);
    height: 150px;
}

& h3 {
    color: white;
}

.container_down {
    background-color: var(--comics-primary);
    font-size: 11px;
    font-weight: bold;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
}

& .row {
    display: flex;
    color: var(--comics-light);
}

& .col {
    display: flex;
    align-items: center;
    justify-content: center;
}

& img {
    height: 50px;
    padding: 0.5rem 0.5rem 0.5rem 1.5rem;
}
</style>