<template>
  <div id="app">
    <app-header/>
    <main>
      <section class="text-center container more">
        <h2>More About Damon Vaughn</h2>
        <p>Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller “The story of my life.”</p>
        <button type="button" class="btn btn-success text-center">Meet the Author</button>
      </section>

      <digital-book/>
      <app-recensioni/>
      <app-events/>
      <app-subscribe/>
      <app-curiosita/>
      <app-articoli/>
      
      
    </main>

    <app-footer/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import DigitalBook from './components/DigitalBook.vue'
import AppRecensioni from './components/AppRecensioni.vue'
import AppEvents from './components/AppEvents.vue' 
import AppSubscribe from './components/AppSubscribe.vue'
import AppCuriosita from './components/AppCuriosita.vue'
import AppArticoli from './components/AppArticoli.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
    DigitalBook,
    AppRecensioni,
    AppEvents,
    AppSubscribe,
    AppCuriosita,
    AppArticoli,
    AppFooter,
    
  }
}
</script>

<style lang="scss">
 @import "./assets/styles/general.scss"; 
#app {
  .more{
    height: 350px;
    
    h2{
      font-size: 70px;
      margin-top: 100px;
      color: #F6BD41
    }
    p{
      font-size: 30px;
    }
  }
}
</style>
