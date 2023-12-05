<script>
import TheHeader from './components/the-header/index.vue';
import TheSidebar from './components/TheSidebar.vue';
import TheBanner from './components/TheBanner.vue';

  export default {
    data() {
        return {};
    },
    components: { TheHeader, TheSidebar, TheBanner }
}
</script>

<template>
  <TheHeader/>
  <div class="main h-[calc(100vh-64px)] flex">
    <TheSidebar/>
    <div class="main-section flex-1 p-6 bg-gray-100 overflow-y-scroll">
      <TheBanner/>
      <div class="product-area mt-8">
        <h1 class="product-title text-2xl font-bold text-gray-700 mb-5">🔥 Hot Deals</h1>
        <div class="product-items grid grid-cols-7 gap-6">
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/jRZnKHr/nintendo-switch.jpg" alt="nintendo-switch">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Nintendo Switch</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/qk326LL/Apple-Mac-Book-Pro.jpg" alt="Apple-Mac-Book-Pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Apple MacBook Pro</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/270STSN/iphone-12-pro-family-hero.jpg" alt="iphone-12-pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">iPhone 12 Pro Max</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/Q68rJFL/canon-eos-r-removebg-preview.png" alt="canon-eos-r">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Canon EOS R</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/3rTvpSF/levant-uhd.webp" alt="levant-uhd">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">AU7000 UHD 4K</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/3rTvpSF/levant-uhd.webp" alt="levant-uhd">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">AU7000 UHD 4K</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/3rTvpSF/levant-uhd.webp" alt="levant-uhd">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">AU7000 UHD 4K</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/3rTvpSF/levant-uhd.webp" alt="levant-uhd">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">AU7000 UHD 4K</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/jRZnKHr/nintendo-switch.jpg" alt="nintendo-switch">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Nintendo Switch</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/qk326LL/Apple-Mac-Book-Pro.jpg" alt="Apple-Mac-Book-Pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Apple MacBook Pro</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/270STSN/iphone-12-pro-family-hero.jpg" alt="iphone-12-pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">iPhone 12 Pro Max</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/Q68rJFL/canon-eos-r-removebg-preview.png" alt="canon-eos-r">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Canon EOS R</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/270STSN/iphone-12-pro-family-hero.jpg" alt="iphone-12-pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">iPhone 12 Pro Max</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
          <div class="product-item">
            <div class="product-image w-full h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/Q68rJFL/canon-eos-r-removebg-preview.png" alt="canon-eos-r">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Canon EOS R</h3>
              <div class="flex items-center justify-between">
                <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
                <div class="product-rating flex items-center my-1">
                  <div class="icons">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-yellow-400">
                      <path fillRule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.007 5.404.433c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.433 2.082-5.006z" clip-rule="evenodd" />
                    </svg>
                  </div>
                  <span class="icon-text text-gray-500 text-sm font-bold mt-[3px] ml-1">4.7</span>
                </div>
                <p class="product-price font-semibold text-gray-700 text-base">$50.99</p>
              </div>
              <div class="product-button pt-2 flex items-center gap-2">
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                  </svg>
                </button>
                <button class="bg-white p-2 rounded-xl shadow flex-1 flex justify-center items-center gap-2 hover:bg-yellow-400 hover:text-white transition duration-300">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-5 h-5">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <p>Details</p>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>