<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <div class="logo">
            <img src="/img/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li><a href="">CHARACTERS</a></li>
                <li><a href="" class="active">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTIBLES</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </nav>

    </header>
</template>


<style scoped>
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

ul {
    list-style: none;
    display: flex;


    & a {
        text-decoration: none;
        font-weight: bold;
        padding: 0.5rem 1rem;
        color: var(--comics-text-header);
    }

    & a.active {
        color: var(--comics-primary);
        border-bottom: 5px solid var(--comics-primary);
    }
}
</style>