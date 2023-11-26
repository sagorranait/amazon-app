<script>
  export default {
    data(){
      return {}
    }
  }
</script>

<template>
  <!-- Header Start -->
  <div class="header h-16 bg-gray-900 flex items-center justify-between px-8">
    <!-- Logo Area Start -->
    <a href="index.html" class="logo w-1/12 h-16 pt-1 flex items-center">
      <img src="../logo.png" alt="Amazon Logo">
    </a>
    <!-- Logo Area End -->
    <!-- Search From Start -->
    <div class="search h-16 bg-gray-900 flex items-center">
      <input class="h-11 w-96 bg-gray-800 border border-gray-500 border-opacity-75 rounded-l-xl px-3 text-white ml-6 focus:outline-none placeholder-white" type="text" id="search" placeholder="Search here...">
      <select name="cars" id="cars" class="h-11 w-36 bg-gray-800 border border-gray-500 border-opacity-75 px-3 text-white focus:outline-none">
        <option class="px-3 h-9">Categories</option>
        <option value="man">Man</option>
        <option value="woman">Woman</option>
        <option value="kid's">Kid's</option>
      </select>
      <button type="submit" class="h-11 w-10 bg-yellow-500 rounded-r-xl flex items-center justify-center text-white">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
        </svg>
      </button>
    </div>
    <!-- Search From End -->
    <!-- Right Icon Area Start -->
    <div class="icons text-white w-48 h-9 flex items-center justify-around">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
      </svg>
      <a href="cart.html" class="cart-icon h-9 w-9 bg-yellow-500 flex items-center justify-center rounded-xl">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
        </svg>
      </a>
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
      </svg>
      <div class="user-icon h-9 w-9 flex items-center justify-center">
        <img class="rounded-xl" src="https://lh3.googleusercontent.com/ogw/ADea4I7_Gy7MS-4GJvxAh_BE5sRDs52xtCfL7UykZtd02w=s83-c-mo" alt="user">
      </div>
    </div>
    <!-- Right Icon Area Css -->
  </div>
  <!-- Header End -->
  <div class="main h-screen flex">
    <div class="main-sidebar w-[12%] bg-gray-900 border-t-2 border-gray-700 p-3">
      <div class="sidebar-categories">
        <div class="categories-lavel text-yellow-500 cursor-pointer flex font-bold p-2 bg-gray-700 rounded-lg">
          <span class="w-8">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z" />
            </svg>
          </span>
          <span>Categories</span>
        </div>
        <div class="subcategories mt-3 p-2">
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Electronics</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Computers</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Smart Home</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Arts & Crafts</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Baby</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Fashion</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Health</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Kitchen</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Toy & Games</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-2 hover:bg-gray-700 rounded-xl p-2">
            <span class="w-4"></span>
            <span>Video Games</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-4 p-2 hover:bg-gray-700 rounded-xl">
            <span class="w-4"><i class="fas fa-percent"></i></span>
            <span>Sell on Amazon</span>
          </div>
          <div class="subcategories-item text-white cursor-pointer flex font-semibold mb-4 p-2 hover:bg-gray-700 rounded-xl">
            <span class="w-7">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </span>
            <span>Help</span>
          </div>

        </div>
      </div>
    </div>
    <div class="main-section flex-1 p-6 bg-gray-100">
      <div class="banner-scetion h-44 rounded-lg flex items-end">
        <a href="#" class="bg-white py-2 px-4 rounded-full m-4 text-bold text-yellow-500">Browse Products</a>
      </div>
      <div class="product-categories mt-10">
        <h1 class="categories-title font-bold text-gray-700 text-2xl flex items-center">
          Popular Categories 
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-yellow-400 mt-1.5 ml-2" viewBox="0 0 20 20" fill="currentColor">
                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
            </svg>
          </span>
        </h1>
        <div class="categories-items mt-5 flex flex-wrap">
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z" />
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19V6l12-3v13M9 19c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zm12-3c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zM9 10l12-3" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
          </a>
          <a href="#" class="categories-item w-20 h-20 bg-white rounded-xl flex items-center justify-center mr-5 mb-5">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01" />
            </svg>
          </a>
        </div>
      </div>
      <div class="product-area mt-5">
        <h1 class="product-title text-2xl font-bold text-gray-700 mb-5">Hot Deals 🔥</h1>
        <div class="product-items flex items-center flex-wrap">
          <div class="product-item mr-5">
            <div class="product-image w-48 h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/jRZnKHr/nintendo-switch.jpg" alt="nintendo-switch">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Nintendo Switch</h3>
              <p class="product-company text-green-700 text-sm font-bold">Nintendo</p>
              <div class="product-rating flex items-center my-1">
                <div class="icons">⭐⭐⭐⭐⭐</div>
                <span class="icon-text text-yellow-300 text-base font-bold mt-1 ml-1">4.7</span>
              </div>
              <p class="product-price font-bold text-gray-700 text-lg">$290.00</p>
            </div>
          </div>
          <div class="product-item mr-5">
            <div class="product-image w-48 h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/qk326LL/Apple-Mac-Book-Pro.jpg" alt="Apple-Mac-Book-Pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Apple MacBook Pro</h3>
              <p class="product-company text-green-700 text-sm font-bold">Apple</p>
              <div class="product-rating flex items-center my-1">
                <div class="icons">⭐⭐⭐⭐⭐</div>
                <span class="icon-text text-yellow-300 text-base font-bold mt-1 ml-1">4.8</span>
              </div>
              <p class="product-price font-bold text-gray-700 text-lg">$1,149.00</p>
            </div>
          </div>
          <div class="product-item mr-5">
            <div class="product-image w-48 h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/270STSN/iphone-12-pro-family-hero.jpg" alt="iphone-12-pro">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">iPhone 12 Pro Max</h3>
              <p class="product-company text-green-700 text-sm font-bold">Apple</p>
              <div class="product-rating flex items-center my-1">
                <div class="icons">⭐⭐⭐⭐⭐</div>
                <span class="icon-text text-yellow-300 text-base font-bold mt-1 ml-1">4.9</span>
              </div>
              <p class="product-price font-bold text-gray-700 text-lg">$1,199.00</p>
            </div>
          </div>
          <div class="product-item mr-5">
            <div class="product-image w-48 h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/Q68rJFL/canon-eos-r-removebg-preview.png" alt="canon-eos-r">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">Canon EOS R</h3>
              <p class="product-company text-green-700 text-sm font-bold">Canon</p>
              <div class="product-rating flex items-center my-1">
                <div class="icons">⭐⭐⭐⭐⭐</div>
                <span class="icon-text text-yellow-300 text-base font-bold mt-1 ml-1">4.3</span>
              </div>
              <p class="product-price font-bold text-gray-700 text-lg">$2,899.00</p>
            </div>
          </div>
          <div class="product-item mr-5">
            <div class="product-image w-48 h-52 bg-white rounded-lg p-4">
              <img class="w-full h-full object-contain" src="https://i.ibb.co/3rTvpSF/levant-uhd.webp" alt="levant-uhd">
            </div>
            <div class="product-details mt-2">
              <h3 class="product-title text-gray-700 font-bold text-base">AU7000 UHD 4K</h3>
              <p class="product-company text-green-700 text-sm font-bold">Samsung</p>
              <div class="product-rating flex items-center my-1">
                <div class="icons">⭐⭐⭐⭐⭐</div>
                <span class="icon-text text-yellow-300 text-base font-bold mt-1 ml-1">4.5</span>
              </div>
              <p class="product-price font-bold text-gray-700 text-lg">$1,488.00</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>