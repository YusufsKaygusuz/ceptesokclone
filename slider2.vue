<template>
    <div>
      <VueSlickCarousel :arrows="true" :dots="true">
        <slide>
      <img src="https://cdnd-tr.ceptesok.com/banner/1440x475/2219d855d62f8cd556af645062db3879.jpg" width="100%">
    </slide>
    <slide>
        <img src="https://cdnd-tr.ceptesok.com/banner/1440x475/7afb336398077288df077d089afdbdd4.jpg" width="100%">
    </slide>
    <slide>
        <img src="https://cdnd-tr.ceptesok.com/banner/1440x475/208131b8e2069f3ecf9e2395ac9db41a.jpg" width="100%">
    </slide>
      </VueSlickCarousel>
    </div>
  </template>
   
  <script>
    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
   
    export default {
        data() {
    return {
      slickOptions: {
    
        arrows: true
      }
    }
  },
      name: 'MyComponent',
      components: { VueSlickCarousel },
    }
  </script> 
  <style scoped>
  img{
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }
 


</style>