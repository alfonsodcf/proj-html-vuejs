<template>
    <header>
        <nav class="d-flex flex-row-reverse">
            <ul>
                <li v-for="(navs, index) in nav" :key="index">
                    <a  :href="navs.url">
                        {{ navs.Text }}
                    </a>
                </li>
       
            </ul>

        </nav>
    <div>
        <img class="logo" src="../assets/img/author-logo-round-small.png" alt="logo">
    </div>
        
        <div class="intestazine">
            <h1>Damon Vaughn</h1>
            <h2>Best-selling author and the most influential public intellectual in the western world right now.</h2>
            <p>- The New York Times</p>
            <div>
                <a href="#">L</a>
                <a href="#">R</a>
            </div>
        </div>
        <div class="book">
            <img src="../assets/img/book-widget.png" alt="book-widget">
            <div class="css-box">
                <h3>Latest Book Release</h3>
                <h4>D. VAUGHN AUTOBIOGRAPHY</h4>
                <P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptate nisi veniam laborum aliquid. Eos officia libero voluptatum obcaecati unde temporibus porro magni impedit facilis, odit officiis nulla amet, aliquid quidem.</P>
            </div>
            <div class="css-bottoni">
                <a href="#">Buy On Amazon</a>
                <a href="#">Buy On AppStore</a>

            </div>
        </div>
        
    </header>
</template>

<script>


export default {
  name: 'AppHeader',
  
      data(){
          return{
              nav:[
                  {
                      Text: 'Home',
                      url: '#',
                      active: true,
                  },
                  {
                      Text: 'About Me',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'Testimonials',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'My Blog',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'Meetups',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'Shop',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'Contact Me',
                      url: '#',
                      active: false,
                  },
                  {
                      Text: 'icona carello',
                      url: '#',
                      active: false,
                  },
              ]
          }
      }
    
  
}
</script>

<style lang="scss">
    header{
        color: white;
        background-image: url(../assets/img/hero-07-2x.jpg);
        background-size: cover;
        background-position: center;
        nav{
            ul{
                list-style: none;
                li{
                    display: inline-block;
                    padding: 20px;

                    a{
                        
                        color: white;
                        &:hover{
                            color: yellow;
                        }
                    }
                }

            }
        }
        .logo{
            margin-left: 100px;
            margin-top: -80px;
        }
    .intestazine{
        width: 100vh;
        padding-left: 100px;
        display: inline-block;
        margin-bottom: 200px;
    }
    .book{
        position: absolute;
        right: 0px;
        bottom: 0px;
        
        background-color: white;
        display: inline-block;

        img{
            vertical-align: top;
        }
        
        .css-box{
            width: 350px;
            display: inline-block;
            color: black;
            margin-bottom: -400px;
            h4{
                color: yellow;
            }
        }
        .css-bottoni{
            text-align: center;
            margin-bottom: 30px;
            a{
                color: black;
                padding: 15px;
                border: 1px solid greenyellow;
            }
        }
    }   
        
    }

</style>
