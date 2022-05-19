<template>
    <section class="container">
        <h2>What The Critics Say</h2>
        <div class="Testimonials">
          <p>TESTIMONIALS FOROM AROUND THE WORLD</p>
          <button type="button" class="btn btn-warning">Reald All Testimonials</button>
          
        </div>
        
        <div>
          <div class="BestAuthor">
            <div>
            <h3>Best Author Of His Generation</h3>
            <hr>
            <h4>This book will change your perspective on life</h4>
            <p>
              Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus. In vitae enim quis sem pharetra.Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem.
            </p>
            <p>
              Donec rutrum congue leo eget malesuada. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut liber. Proin eget tortor risus. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Donec rutrum congue leo eget malesuada.
            </p>
            <button type="button" class="btn btn-dark">Dark</button>
            </div>
          </div>
          
          <div class="recensini">
            <div class="rece1 text-center">
              <h5>A True Masterpiece, Bravo!</h5>
              <p>
                Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feug at.
              </p>
            </div>
            <p class="pcard">Gerald Hendley, The Guardian</p>

            <div class="rece1 text-center">
              <h5>A True Masterpiece, Bravo!</h5>
              <p>
                Donec sollicitudin molestie malesuada. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Nulla quis lorem ut libero malesuada feugiat. Vestibulum ac diam sit amet.
              </p>
            </div>
            <p class="pcard">Gerald Hendley, The Guardian</p>

          </div>
        </div>
        
    </section>
    
</template>

<script>
export default {
  name: 'AppRecensioni',
  
}
</script>

<style lang="scss" scoped>
  h2{
    padding-top: 50px;
    font-size: 40px;
  }

  section{
    margin-bottom: 30px;
  }
  .Testimonials{
    margin-bottom: 20px;
    p{
      display: inline-block;
      color: #49A987;
      margin-right: 40vw;
    }
    button{
      color: white;
    }
    
  }
  .BestAuthor{
    background-image: url(../assets/img/testimonial2-2x.jpg);
    background-size: cover;
    background-position: center;
    width: 40vw;
    color: white;
    display: inline-block;
    margin-right: 80px;
    vertical-align: top;
    h3{
      font-size: 38px;
      padding-bottom: 20px;
    }
    h4{
      font-size: 20px;
      padding-top: 20px;
      padding-bottom: 10px;
    }
    div{
      padding: 70px;
    }
  }
  .recensini{
    display: inline-block;
    width: 22vw;
    .rece1{
      background-color: #FEF7E9;
      padding: 20px;
    }
    .pcard{
      padding-top: 15px;
      padding-bottom: 15px;
    }

  }

    
</style>