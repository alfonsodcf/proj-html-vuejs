<template>
    <section class="container">
        <h2>What The Critics Say</h2>
        <div class="Testimonials">
          <p>TESTIMONIALS FOROM AROUND THE WORLD</p>
          <button type="button" class="btn btn-warning">Warning</button>
          
        </div>
        
        <div>
          <div class="BestAuthor">
            <div>
            <h3>Best Author Of His Generation</h3>
            <hr>
            <h4>This book will change your perspective on life</h4>
            <p>
              Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus. In vitae enim quis sem pharetra.Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Donec rutrum congue leo eget malesuada. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut liber. Proin eget tortor risus. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Donec rutrum congue leo eget malesuada.
            </p>
            <button type="button" class="btn btn-dark">Dark</button>
            </div>
          </div>
          
          <div class="recensini">
            <div class="rece1 text-center">
              <h5>A True Masterpiece, Bravo!</h5>
              <p>
                Nulla quis lorem ut libero malesuada feugiat Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feug at.
              </p>
            </div>
            <p>Gerald Hendley, The Guardian</p>

            <div class="rece1 text-center">
              <h5>A True Masterpiece, Bravo!</h5>
              <p>
                Nulla quis lorem ut libero malesuada feugiat Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feug at.
              </p>
            </div>
            <p>Gerald Hendley, The Guardian</p>

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
    padding-top: 30px;
  }
  section{
    margin-bottom: 30px;
  }
  .Testimonials{
    p{
      display: inline-block;
    }
  }
  .BestAuthor{
    background-image: url(../assets/img/testimonial2-2x.jpg);
    background-size: cover;
    background-position: center;
    width: 35vw;
    color: white;
    display: inline-block;
    margin-right: 40px;
    vertical-align: top;
    div{
      padding: 70px;
    }
  }
  .recensini{
    display: inline-block;
    width: 25vw;
    .rece1{
      background-color: #FEF7E9;
      padding: 20px;
    }

  }

    
</style>