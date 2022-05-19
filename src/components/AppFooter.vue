<template>
    <footer>
        
        <div>
            <div class="cs-griglia">
                <img class="logo" src="../assets/img/author-logo-round-small.png" alt="logo">
            </div>
            <div class="cs-griglia about">
                <h3>ABOUT ME</h3>
                <p>Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feugiat. Vivamus suscipit tortor eget felis porttitor volutpat.</p>
            </div>

            <div class="cs-griglia links">
                <h3>USEFUL LINKS</h3>
                <ul>
                    <li><a href="#">Latest Books</a></li>
                    <li><a href="#">Upcoming Events</a></li>
                    <li><a href="#">Recent Articles</a></li>
                    <li><a href="#">Business Enquiries</a></li>
                    <li><a href="#">Visit My Foundation</a></li>
                    
                </ul>
            </div>

            <div class="cs-griglia contact">
                <h3>CONTACT INFO</h3>
                <ul>
                    <li>63 E. Studebaker Street Bolingbrook, IL 60440</li>
                    <li>Phone: (800) 000-0000</li>
                    <li>Mobile: (800) 000-0000</li>
                    <li>Email:<a href="#">info@your-company.com</a></li>
                </ul>
            </div>
        </div>

        <p class="text-center">© Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>

    </footer>
    
</template>

<script>
export default {
    nome: 'AppFooter',
}

</script>

<style lang="scss" scoped>
    footer{
      background-image: url(../assets/img/hero-07-2x.jpg);
        background-size: cover;
        background-position: top;
        height: 520px;  
        color: white;
        .cs-griglia{
            display: inline-block;
            vertical-align: top;
            
            margin: 80px;
            margin-top: 100px;
           a{
                color: white;
                &:hover{
                    color: #F6BD41;
                }
           }
        }
        .about{
            width: 300px;
        }
        .links{
            
        }
        .contact{
            ul{
                list-style: none;
            }
        }
    }

</style>