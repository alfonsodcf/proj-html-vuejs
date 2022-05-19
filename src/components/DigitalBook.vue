<template>
    <section>
        <div class="text-center logi">
            <img src="../assets/img/ebay-logotan-2x.png" alt="ebay">
            <img src="../assets/img/audible-logotan-2x.png" alt="audible">
            <img src="../assets/img/bb-logotan-2x.png" alt="bn-logo">
            <img src="../assets/img/kindlefire-logotan-2x.png" alt="kindlefire">
        </div>
        <div class="audiobook">
            
            <img class="telefono" src="../assets/img/audible-app-2x.png" alt="audible-app">

            <div class="info text-center">
                <h3>New Audiobook</h3>
                <p>NO TIME READ? NO PROBLEM. LISTEN TO IT</p>
                <P>Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue corsus.</P>
                <div>
                    <img src="../assets/img/audible-logo.png" alt="audible-logo">
                    <img src="../assets/img/bn-logo-tall.png" alt="logo-tall">
                    <img src="../assets/img/kindle-logo-tall.png" alt="logo-tall">
                </div>
            </div>

            
            
        </div>
    </section>
</template>

<script>
export default {
 nome: 'DigitalBook',
}

</script>

<style lang="scss" scoped>
    .logi{
        background-color: #FEF7E9;
        img{
            width: 200px;
            padding: 20px;
        }
    }
    .audiobook{
        background-image: url(../assets/img/banner.jpg);
        background-size: cover;
        background-position: center;
        position: relative;
        height: 600px;
      
        .telefono{
            position: absolute;
            left: 350px;
            bottom: 0px;
            width: 30rem;
        };

        .info{
            position: absolute;
            right: 350px;
            width: 35rem;
            padding-top: 200px;
            color: white;
            img{
                padding: 20px;
            }
        }
    }

</style>