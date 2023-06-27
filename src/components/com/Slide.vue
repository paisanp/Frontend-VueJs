<template>
    <swiper
      :slidesPerView="3"
      :spaceBetween="0"
      :pagination="{
        clickable: true,
      }"
      :modules="modules"
      class="mySwiper"
    >
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_1_edit1.png?v=202305101549" alt=""></swiper-slide>
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_2_edit1.png?v=202305101549" alt=""></swiper-slide>
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_3_edit1.png?v=202305101549" alt=""></swiper-slide>
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_4.png?v=202305101549" alt=""></swiper-slide>
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_5.png?v=202305101549" alt=""></swiper-slide>
      <swiper-slide><img class="img-slide" src="https://image.makewebeasy.net/makeweb/m_1920x0/m14BHwk4P/Home%2F06___Slide_6.png?v=202305101549" alt=""></swiper-slide>
    </swiper>
  </template>
  <script>
    // Import Swiper Vue.js components
    import { Swiper, SwiperSlide } from 'swiper/vue';
  
    // Import Swiper styles
    import 'swiper/css';
  
    import 'swiper/css/pagination';
    
    // import required modules
    import { Pagination } from 'swiper';
  
    export default {
      components: {
        Swiper,
        SwiperSlide,
      },
      setup() {
        return {
          modules: [Pagination],
        };
      },
    };
  </script>

<style>
.img-slide {
    width: 500px;
    height: auto;
}
</style>