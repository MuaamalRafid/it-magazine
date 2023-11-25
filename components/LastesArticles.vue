<template>
  <div>
    <div class="container mx-auto mt-10 mb-4 text-black dark:text-white">
      <h1  
        class="mx-3 mb-1 text-xl font-bold sm:text-2xl md:text-3xl font-cairo"
        v-motion-slide-right
      >
        اخر المقالات
      </h1>

      
      <div class="flex flex-col justify-center gap-4 p-4 sm:flex-row sm:justify-between md:gap-40 sm:gap-20">
     
        <!-- main article  -->
        <div class="md:w-[50%] sm:w-[40%] flex flex-col gap-2 " 
        v-motion-pop-visible
    >
      
          <img class="rounded-md " src="/1283866.jpg" alt="">
          <div class="flex items-center justify-between">
             <div class="flex items-center gap-2 justify-normal">
              <div class="w-8 h-8 bg-red-500 rounded-full">
                <img  class="rounded-full" src="/107749.png" alt="">
              </div>
              <p>مؤمل رافد</p>
             </div>
              <p>2023-11-3</p>
          </div>
          <div>
            <h1 class="text-xl font-bold sm:text-3xl">title</h1>
            <p class="line-clamp-3 sm:text-md md:text-xl">يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها، وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا يُمكن نسيانها، حيث يحتضن الأحباب، ...</p>
          </div>
        </div>

        <div class="grid grid-cols-2 gap-4 sm:gap-6 sm:flex sm:flex-col md:w-[50%] sm:w-[50%]  "       >
   
          <div class="flex flex-col gap-3 sm:flex-row " v-motion-slide-visible-top>
            <img class="rounded-md md:w-[50%] sm:w-[50%]" src="/1283866.jpg"  alt="">
         
          <div class="">
        <h1 class="self-center text-lg font-bold sm:text-lg md:text-2xl">title</h1>
        <p class="text-sm sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"> يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها، وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا يُمكن نسيانها، حيث يحتضن الأحباب، ... </p>
          </div>
          </div>

             <div class="flex flex-col gap-3 sm:flex-row" v-motion-slide-visible-top>
            <img class="rounded-md sm:w-[50%]" src="/1283866.jpg"  alt="">
         
          <div class="">
               <h1 class="self-center text-lg font-bold sm:text-lg md:text-2xl">title</h1>
            <p class="text-sm sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"> يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها، وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا يُمكن نسيانها، حيث يحتضن الأحباب، ... </p>
          </div>
          </div>

             <div class="flex flex-col gap-3 sm:flex-row " v-motion-slide-visible-top>
            <img class="rounded-md sm:w-[50%]" src="/1283866.jpg"  alt="">
         
          <div class="">
                <h1 class="self-center text-lg font-bold sm:text-lg md:text-2xl">title</h1>
             <p class="text-sm sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3 "> يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها، وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا يُمكن نسيانها، حيث يحتضن الأحباب، ... </p>
          </div>
          </div>

             <div class="flex flex-col gap-3 sm:hidden ">
            <img class="rounded-md " src="/1283866.jpg"  alt="">
         
          <div class="">
            <h1 class="self-center text-lg font-bold ">title</h1>
            <p class="text-sm sm:text-lg md:text-2xl line-clamp-2 "> يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها، وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا يُمكن نسيانها، حيث يحتضن الأحباب، ... </p>
          </div>
          </div>
          
          
        
          
     
        </div>
      


        <!-- <div class="w-[30%] flex flex-col gap-4">
          <div class="flex gap-4">
            <img class="rounded-md" src="/1283866.jpg" alt="">
       
          </div>
          

        </div> -->

      

        
  
      
    


      </div>
           <hr class="dark:border-[#61696d] bordr-[#1d2325] border-1">
    </div>
  </div>
</template>
<script setup>
const initial = ref({
  y: 100,
  opacity: 0,
})

const enter = ref({
  y: 0,
  opacity: 1,
});
</script>