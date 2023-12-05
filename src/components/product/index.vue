<script>
import Single from './Single.vue';

  export default {
    components: { 
      Single, 
    }
  }
</script>

<template>
  <div class="product-area mt-8">
    <h1 class="product-title text-2xl font-bold text-gray-700 mb-5">🔥 Hot Deals</h1>
    <div class="product-items grid grid-cols-7 gap-6">
      <Single v-for="index in 14" :key="index" />
    </div>
    <div class="flex items-center justify-center pt-10">
      <button class="px-5 py-2 text-white bg-yellow-500 flex items-center justify-center rounded-xl">Browse More</button>
    </div>
  </div>
</template>