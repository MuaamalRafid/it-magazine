 <template>
<div class="relative bg-[#f4f4f4] dark:bg-black scroll-smooth">
  <Header/>
    <button class="sticky top-0 flex items-center justify-center px-3 py-2 bg-blue-400 right-6" @click="setColorTheme($colorMode.preference=='dark'?'light':'dark')">dark</button>
    
 <NuxtPage />
 <!-- <Footer/> -->
</div>
</template>

<script setup lang="ts">
useHead(
  {
    htmlAttrs: { dir: 'rtl', lang: 'ar' }
  }
);

type Theme = "light" | "dark";
const setColorTheme = (newTheme: Theme) => {
  useColorMode().preference = newTheme;
};

</script>
