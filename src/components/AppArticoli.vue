<template>
    <section>
        <div class="container">
            <h2>Recent Articles</h2>
            <p>READ THE LATEST ENTRIES</p>
            <button type="button" class="btn btn-warning">Warning</button>
            <div>
                <div class="Suggerimenti">
                    <img src="../assets/img/20-Tips-scaled.jpg" alt="Tips-scaled">
                    <h3>20 Creativity Tips</h3>
                    <p>By admin|October 24th, 2019|Categories: Event, Tips & Tricks</p>
                    <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet.</p>
                </div>

                <div class="Suggerimenti2">
                    <img src="../assets/img/thumb-13-2x-700x441.jpg" alt="thumb">
                    <h3>What’s On Your Booklist?</h3>
                    <p>By Mary Maxey October 24, 2019</p>
                    <img src="../assets/img/thumb-08-2x-700x441.jpg" alt="thumb">
                    <h3>Istanbul Travel Guide</h3>
                    <p>By Mary Maxey October 24, 2019</p>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    nome: 'AppArticoli',
}

</script>

<style lang="scss" scoped>
    section{
        background-color: #FEF7E9;
        p{
            display: inline-block;
        }
        .Suggerimenti{
            display: inline-block;
            background-color: white;
            padding: 20px;
            width: 44vw;
            margin-right: 30px;
            img{
                width: 100%;
            }
        }
        .Suggerimenti2{
            display: inline-block;
            background-color: white;
            padding: 20px;
            width: 21vw;
            img{
                width: 100%;
            }
        }
    }

</style>