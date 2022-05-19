<template>
    <section class="text-center">
        <h2>Subscribe To My <br> Newsletter</h2>
        <p class="p1">BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</p>
        <input type="search" placeholder="Insert your email...*" aria-label="Search">
        <button type="button" class="btn btn-success">Success</button>
        <p class="p2">Donec fringilla nunc eu turpis dignissim, at euismod sapien <br> tincidunt.</p>

    </section>
</template>

<script>
export default {
    nome: 'AppSubscribe',
}

</script>

<style lang="scss" scoped>

section{
    background-image: url(../assets/img/banner-2.jpg);
    background-size: cover;
    background-position: center;
    color: white;
    padding: 100px;
    .p1{
        color:#F6BD41;
        
    }
    input{
        margin-right: 20px;
        padding: 10px;
        margin-bottom: 20px;
    }
    .p2{
        color: gray;
    }
}

</style>