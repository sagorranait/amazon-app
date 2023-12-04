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
    <div class="main-section flex-1 p-6 bg-gray-100">
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
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>