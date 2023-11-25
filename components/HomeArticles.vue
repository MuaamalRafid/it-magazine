<template>
  <div>
    <div class="container mx-auto dark:text-white twxt-black">
      <div class="flex flex-col gap-5 mt-10">
        <div v-motion-slide-visible-right>
          <div class="flex flex-col items-center justify-center gap-3">
            <h1
              class="pr-2 text-lg font-bold text-center font-cairo sm:text-xl md:text-2xl"
            >
              مقالات ادبية
            </h1>
            <hr class="w-[5%]" />
          </div>
            
             
            
            
          
            
            
           
            
           
            
          
        </div>
        <div v-motion-slide-visible-right>
          <div class="flex flex-col items-center justify-center gap-3">
            <h1
              class="pr-2 text-lg font-bold text-center font-cairo sm:text-xl md:text-2xl"
            >
              مقالات تقنية
            </h1>
            <hr class="w-[5%]" />
          </div>
             
   
     
        </div>
        <div
          v-motion
          :enter="{
            transition: {
              delay: 4000,
            },
          }"
        >
          <div class="flex flex-col items-center justify-center gap-3">
            <h1
              class="pr-2 text-lg font-bold text-center font-cairo sm:text-xl md:text-2xl"
            >
              مقالات دينية
            </h1>
            <hr class="w-[5%]" />
          </div>

     
        </div>
      </div>
    </div>
    <hr class="dark:border-[#61696d] bordr-[#1d2325] border-1" />
  </div>
</template>

<script>

</script>
