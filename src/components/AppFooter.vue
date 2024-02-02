<script>
export default {
}
</script>

<template>
    <footer>
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
        <div class="footer_top">
            <section>
                <h3>DC COMICS</h3>
                <p>Characters</p>
                <p>Comics</p>
                <p>Movies</p>
                <p>TV</p>
                <p>Games</p>
                <p>Videos</p>
                <p>News</p>
                <h3>SHOP</h3>
                <p>Shop Dc</p>
                <p>Shop Dc Collectibles</p>
            </section>

            <section>
                <h3>DC</h3>
                <p>Terms Of Use</p>
                <p>Privacy policy (New)</p>
                <p>Ad Choices</p>
                <p>Advertising</p>
                <p>Jobs</p>
                <p>Subscriptions</p>
                <p>Talent Workshops</p>
                <p>CPSC Certificates</p>
                <p>Ratings</p>
                <p>Shop Help</p>
                <p>Contact Us</p>
            </section>

            <section>
                <h3>SITES</h3>
                <p>DC</p>
                <p>MAD Magazine</p>
                <p>DC Kids</p>
                <p>DC Universe</p>
                <p>DC Power Visa</p>

            </section>

        </div>
        <div class="footer_bottom">
            <button>SIGN-UP NOW!</button>
            <div class="row">
                <h2>FOLLOW US</h2>
                <img src="/img/footer-facebook.png" alt="">
                <img src="/img/footer-twitter.png" alt="">
                <img src="/img/footer-youtube.png" alt="">
                <img src="/img/footer-pinterest.png" alt="">
                <img src="/img/footer-periscope.png" alt="">
            </div>
        </div>
    </footer>
</template>


<style scoped>
footer {
    background-image: url(/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 100%;
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
    justify-content: space-between;
    align-items: center;
}

& img {
    height: 50px;
    padding: 0.5rem 0.5rem 0.5rem 1.5rem;
}

.footer_top {
    background-image: url(/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    height: 400px;
    background-position: right center;
    color: white;
    display: flex;
}

& section {
    padding: 0.5rem 1rem;
}

& p {
    color: var(--comics-footer);
    font-size: 14px;
    font-weight: bold;
}

.footer_bottom {
    background-color: var(--comics-footer-bottom);
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

& button {
    background-color: var(--comics-footer-bottom);
    font-weight: bold;
    color: var(--comics-light);
    margin-left: 1rem;
    padding: 1rem;
    border: solid 5px var(--comics-primary);
}

& .row h2 {
    color: var(--comics-primary);
}
</style>