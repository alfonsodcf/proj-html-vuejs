<template>
  <div id="app">
    <app-header/>
    <main>
      <section class="text-center container">
        <h2>Mone About Damon Vaughn</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem eius nulla suscipit natus mollitia. Adipisci minus vero quis, voluptate quod ullam quidem tenetur, rerum nihil deserunt debitis totam. Alias, rem.</p>
        <button type="button" class="btn btn-success text-center">Success</button>
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
  
}
</style>
