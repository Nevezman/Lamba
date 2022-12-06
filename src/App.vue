<template >
  <header>
    <HeaderVue/>
  </header>
  <main class="main">
    <section class="promo">
      <div class="conteiner">
        <PromoVue/>
      </div>
    </section>
    <section class="info">
      <div class="conteiner">
         <InfoVue/>
      </div>
    </section>
    <section class="track">
      <div class="conteiner">
        <TrackVue/>
      </div>
    </section>
    <section class="superEvo">
        <SuperEvoVue/>
    </section>
    <section class="blog">
      <div class="conteiner">
        <BlogVue/>
      </div>
    </section>
  </main>
    
  
</template>
<script>
import BlogVue from './components/Blog.vue';
import SuperEvoVue from './components/SuperEvo.vue';
import TrackVue from './components/Track.vue';
import InfoVue from './components/Info.vue';
import HeaderVue from './components/Header.vue';
import PromoVue from './components/Promo.vue';
export default {
  components:{
    HeaderVue, PromoVue, InfoVue, TrackVue,SuperEvoVue,BlogVue 
  }
}
</script>
<style>

  html {
    box-sizing: border-box;
  }
  *,
  *::after,
  *::before {
    box-sizing: inherit;
  } 
  a {
    color:inherit;
    text-decoration: none;
  }
  .conteiner {
    max-width: 920px;
    padding: 0 10px;
    margin: 0 auto;
  }
  body {
    font-family: 'Roboto Condensed', sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    color: #040404;
    line-height: 1.2;
  }
  header {
    padding-top: 25px;
    position: absolute;
    left: 0;
    right: 0;
  }
  h3 {
    font-style: normal;
    font-weight: 300;
    font-size: 32px;
    text-transform: uppercase;
  }
    
  
  .promo {
    background-image: url(./assets/Jpg/Promo.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    text-align: center;
    
  }
  .track {
    background-image: url(./assets/Jpg/gran_final.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    
    
  }
</style>