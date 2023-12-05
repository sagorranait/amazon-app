<script>
import TheHeader from './components/the-header/index.vue';
import TheSidebar from './components/TheSidebar.vue';
import TheBanner from './components/TheBanner.vue';
import Product from './components/product/index.vue';

  export default {
    data() {
        return {};
    },
    components: { 
      Product, 
      TheHeader, 
      TheBanner, 
      TheSidebar, 
    }
  }
</script>

<template>
  <TheHeader/>
  <div class="main h-[calc(100vh-64px)] flex">
    <TheSidebar/>
    <div class="main-section flex-1 p-6 bg-gray-100 overflow-y-scroll">
      <TheBanner/>
      <Product/>
    </div>
  </div>
</template>