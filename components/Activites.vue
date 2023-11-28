<template>
  <div>
    <div class="container flex flex-col m-auto mt-10 mb-10">
        
    <div class="space-y-4">
      <h1 class="text-3xl text-center">ابرز النشاطات</h1>
        <Splide
        :options="{
          type: 'loop',

          rewind: false,

          arrows: false,
          drag: true,
          autoplay: true,
          direction: 'rtl',
          perPage: 1,
          interval:3000,
          pagination: false,
        }"
        class="px-2 md:px-16"
      >
        <SplideSlide>
         
            <img
              src="/1283866.jpg"
              class="absolute top-0 right-0 w-full rounded-md h-96"
              alt=""
            />
  
        </SplideSlide>
           <SplideSlide>
    
            <img
              src="/1283866.jpg"
              class="top-0 right-0 w-full rounded-md h-96"
              alt=""
            />
     
        </SplideSlide>
           <SplideSlide>
     
            <img
              src="/1283866.jpg"
              class="top-0 right-0 w-full rounded-md h-96"
              alt=""
            />
          
        </SplideSlide>
           <SplideSlide>
      
            <img
              src="/Frame 5.png"
              class="top-0 right-0 w-full rounded-md h-96"
              alt=""
            />
        
        </SplideSlide>
      </Splide>
    </div>
    
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
</style>
