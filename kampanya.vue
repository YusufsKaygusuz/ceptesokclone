<template>
  <div>
    <section class="section home-slider dark home-campaigns">
      <div class="wrapper mobile-wide">
        <div class="slider-heading">
          <h2 class="heading-title">Kampanyalar</h2>
          <a
            class="heading-cta link-to-pages-campaignList"
            href="/kampanya-listesi"
            >Tüm Kampanyalar</a
          >
        </div>
        <VueSlickCarousel :arrows="true" :dots="false" :slidesToShow="3">
        <div
          id="slider_r1nxvebcz"
          class="swiper-container slider-container slider-slider bz slider-auto-slides swiper-container-initialized swiper-container-horizontal"
        >
          <div
            class="swiper-wrapper"
           
          >
            
          <div class="swiper-slide swiper-slide-visible swiper-slide-next">
              <button class="campaigns-item">
                <div class="image item-bg imagewrap bg">
                  <img src="../assets/kategori1.jpg">

                </div>
              </button>
            </div>
            <div class="swiper-slide swiper-slide-visible swiper-slide-active">
              <button class="campaigns-item">
                <div class="image item-bg imagewrap bg">
                  <img src="../assets/kategori2.jpg">

                </div>
              </button>
            </div>
            <div class="swiper-slide swiper-slide-visible swiper-slide-next">
              <button class="campaigns-item">
                <div class="image item-bg imagewrap bg">
                  <img src="../assets/kategori3.jpg">

                </div>
              </button>
            </div>
            <div class="swiper-slide swiper-slide-visible">
              <button class="campaigns-item">
                <div class="image item-bg imagewrap bg">
                  <img src="../assets/kategori4.jpg">

                </div>
              </button>
            </div>
            <div class="swiper-slide swiper-slide-visible">
              <button class="campaigns-item">
                <div class="image item-bg imagewrap bg">
                  <img src="../assets/kategori5.jpg">

                </div>
              </button>
            </div>
          
          </div>
          <span
            class="swiper-notification"
            aria-live="assertive"
            aria-atomic="true"
          ></span>
        </div>
        </VueSlickCarousel>
      </div>
    </section>
  </div>
</template>

<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script>
