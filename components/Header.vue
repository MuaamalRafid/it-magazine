<template>
  <div>
    <header
      v-motion
    :initial="{ opacity: 0, y: 80 }"
    :enter="{ opacity: 1, y: 0, scale: 1 }"
    :variants="{ custom: { scale: 4 } }"
    :delay="100"
      class="container relative flex items-center justify-between m-auto text-black dark:text-white sm:flex-row-reverse h-28 sm:justify-between"
    >
     <div class="flex items-center gap-4">
        <div class="items-center hidden gap-4 sm:flex">
        <button>تسجيل  الدخول</button>
     </div>
     <div class="w-8 h-8 mr-5 bg-blue-500 rounded-full sm:m-0">
        <img  class="rounded-full" src="/107749.png" alt="">
     </div>
     </div>
      <div class="flex items-center justify-between sm:gap-8 ">
        <NuxtLink to="/">
          <img v-if="$colorMode.preference=='dark'"
            src="/darkLogo.png"
            class="w-24 sm:w-28"
            alt=""
          />
           <img v-if="$colorMode.preference=='light'"
            src="/lightLogo.png"
            class="w-24 sm:w-28"
            alt=""
          />
        </NuxtLink>
        <div class="items-center hidden gap-7 sm:flex">
          <NuxtLink to="/AboutAs">من نحن</NuxtLink>
          <NuxtLink to="/Articles">المقالات</NuxtLink>
          <NuxtLink to="/">اصدارات المجلة</NuxtLink>
        </div>
     
      </div>
        <button @click="showOption" class="w-12 sm:hidden">
         <Icon v-if="refShowOption"  name="ic:outline-menu" size="25px"></Icon>
         <Icon v-else  name="ic:outline-menu" rotate="3" size="25px"></Icon>
       </button>
       <div v-if="refShowOption" class="absolute -bottom-20 w-56 bg-black border border-[#1d2325] px-4 flex flex-col gap-2 justify-center items-center left-3 sm:hidden">
        <NuxtLink to="/AboutAs">من نحن</NuxtLink>
        <hr class="border-white border-1">
          <NuxtLink to="/Articles">المقالات</NuxtLink>
          <NuxtLink to="/">اصدارات المجلة</NuxtLink>
       </div>
    </header>
  </div>
</template>

<script setup lang="ts">
const refShowOption = ref(false);
const showOption = () => {
  refShowOption.value = !refShowOption.value;
};
type Theme = "light" | "dark";
const setColorTheme = (newTheme: Theme) => {
  useColorMode().preference = newTheme;
};
</script>
