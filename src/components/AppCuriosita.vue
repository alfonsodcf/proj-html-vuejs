<template>
    <section class="container">
        <h2 class="text-center">Dig A Little Deeper Into Damon Vaughn</h2>
        <p class="text-center find">FIND OUT MORE ABOUT THE AUTHOR HIMSELF</p>
        <div>
            <div class="about text-center">
                <h3>About Me</h3>
                <hr>
                <p>A Brief Biography Of Damon Vaughn</p>

            </div>

            <div class="book text-center">
                <h3>About Me</h3>
                <hr>
                <p>A Brief Biography Of Damon Vaughn</p>

            </div>

            <div class="signing text-center">
                <h3>About Me</h3>
                <hr>
                <p>A Brief Biography Of Damon Vaughn</p>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    nome: 'AppCuriosita',
}

</script>

<style lang="scss" scoped>

    section{
        margin-top: 50px;
        color: white;
        margin-bottom: 80px;
        h2{
            color: black;
        }
        .find{
            color: #49A987;
        }
        p{
            color: #F6BD41 ;

        }
        h3{
            padding-top: 95%;
        }
    }

    .about{
        background-image: url(../assets/img/box-1.jpg);
        background-size: cover;
        background-position: center;
        width: 20vw;
        height: 500px;
        display: inline-block;
        margin: 20px;
        
        
    }

     .book{
        background-image: url(../assets/img/box-4.jpg);
        background-size: cover;
        background-position: center;
        width: 20vw;
        height: 500px;
        display: inline-block;
        margin: 20px;
        
    }

     .signing{
        background-image: url(../assets/img/box-3.jpg);
        background-size: cover;
        background-position: center;
        width: 20vw;
        height: 500px;
        display: inline-block;
        margin: 20px;
      
    }
</style>