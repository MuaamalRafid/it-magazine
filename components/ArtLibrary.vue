<template>
  <div>
    <div class="container m-auto">
      

      <div class="space-y-4">
<h1 class="text-3xl text-center">المكتبة الفنية</h1>
           <Splide
        :options="{
          type: 'loop',

          arrows: true,
          drag: true,
          autoplay: true,
          direction: 'rtl',
          perPage: 7,
          rewind: false,
          pagination: false,
          interval: 3000,
          gap: '1rem',
          focus: 'center',
          breakpoints: {
            640: {
              perPage: 2,
               arrows: false,
            },
            768: {
              perPage: 3,
            },
            1024: {
              perPage: 7,
            },
          },
        }"
        class="px-2 md:px-16"
      >
        <SplideSlide>

            <img
            
              src="/المكتبة الفنية/161339-غوستاف-كليمت.jpg"
              class="h-44 w-44"
              alt=""
            />
    
        </SplideSlide>
        <SplideSlide>
          
            <img
              src="/المكتبة الفنية/2111870093_08715121ba_o.jpg"
              class="h-44 w-44"
              alt=""
            />
   
        </SplideSlide>
        <SplideSlide>
         
            <img
              src="/المكتبة الفنية/NQvIV0a0Po-Annajah.jpg_729x410.jpg"
              class="h-44 w-44"
              alt=""
            />
        
      

        </SplideSlide>
        <SplideSlide>
         
            <img
              src="/المكتبة الفنية/The_Lady_of_Shalott-1.webp"
              class="h-44 w-44"
              alt=""
            />
       
        </SplideSlide>
        <SplideSlide>
        
            <img
              src="/المكتبة الفنية/٢٠٢٠٠٤٠٧١٩٣٠١٦.jpg"
              class="h-44 w-44"
              alt=""
            />
         
        </SplideSlide>
      </Splide>
      </div>
      <!-- <Splide
        :options="{
          type: 'fade',
          rewind: true,
          pagination: false,
          arrows: false,
          isNavigation: true,
        }"
      >
      <SplideSlide>
        <div class="mb-0 mx-36">
          <img src="/1283866.jpg" class="" alt="" />
        </div>
      </SplideSlide>
      </Splide> -->

        <hr class="dark:border-[#61696d] bordr-[#1d2325] border-1 mt-10" />
   
    </div>
  </div>
</template>

<script setup>
import { Splide, SplideSlide } from "@splidejs/vue-splide";
import "@splidejs/splide/css";

</script>

<style>
.arrows {
  background-color: transparent;
}
.splide__arrow {
  background-color: transparent;
}
.splide__arrow svg {
  fill: antiquewhite;
}

.splide__slide {
  opacity: 0.6;
}

.splide__slide.is-active {
  opacity: 1;
}

</style>
