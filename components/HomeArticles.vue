<template>
  <div>
    <div class="container mx-auto dark:text-white twxt-black">
      <div class="flex flex-col gap-5 mt-10">
        
        <h1 class="text-3xl">مقالات ادبية</h1>
       <Splide :options=" {
  type   : 'loop',
 
  rewind:false,

  arrows:true,
  drag:true,
  autoplay:true,
  direction: 'rtl',
  perPage: 3,
  gap: 12,
  breakpoints: {
    640: { perPage: 2, arrows:false },
    768: { perPage: 3 },
    1024: { perPage: 3, },
  },
  pagination:false,
  classes:{
    arrows:'splide__arrows arrows ',
    arrow : 'splide__arrow ',
		prev  : 'splide__arrow--prev  prev',
		next  : 'splide__arrow--next next',
  }
} "  class="p-2 md:p-16">
        
       

          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
     
    

  </Splide>
          <h1 class="text-3xl">مقالات ادبية</h1>

       <Splide :options=" {
  type   : 'loop',
 
  rewind:false,

  arrows:true,
  drag:true,
  autoplay:true,
  direction: 'rtl',
  perPage: 3,
  gap: 12,
  breakpoints: {
    640: { perPage: 2, arrows:false },
    768: { perPage: 3 },
    1024: { perPage: 3, },
  },
  pagination:false,
  interval:3000,
} " class="p-2 md:p-16">
        
       

          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
     
    

  </Splide>
          <h1 class="text-3xl">مقالات ادبية</h1>

         <Splide :options=" {
  type   : 'loop',
 
  rewind:false,

  arrows:true,
  drag:true,
  autoplay:true,
  direction: 'rtl',
  perPage: 3,
  gap: 12,
  breakpoints: {
    640: { perPage: 2, arrows:false },
    768: { perPage: 3 },
    1024: { perPage: 3, },
  },
  pagination:false,
} " class="p-2 md:p-16" >
        
       

          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
          <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
               <SplideSlide>
                 <div class="flex-col items-center sm:flex">
              <img class="rounded-md" src="/1283866.jpg" alt="" />

              <div class="flex flex-col items-center justify-center gap-2 mt-2">
                <h1 class="text-sm font-bold sm:text-xl md:text-2xl">
                  عنوان المقالة
                </h1>
                <p
                  class="text-xs sm:text-md md:text-lg line-clamp-2 sm:line-clamp-3"
                >
                  يُعرّف الوطن على أنَّه الأرض التي وُلد فيها الإنسان، ونشأ بها،
                  وترعرع في أرجائها، وتزوّج فيها، فهو يُمثّل الذكريات التي لا
                  يُمكن نسيانها، حيث يحتضن الأحباب، ...
                </p>
              </div>
        </div>
            </SplideSlide>
     
    

  </Splide>
      </div>
    </div>
    <hr class="dark:border-[#61696d] bordr-[#1d2325] border-1" />
  </div>
</template>

<script setup>
import { Splide, SplideSlide } from '@splidejs/vue-splide';
import '@splidejs/splide/css';


</script>


<style>
.arrows{
  background-color: transparent;
}
.splide__arrow{
  background-color: transparent;
  
}
.splide__arrow svg{

  fill: antiquewhite;
}


</style>