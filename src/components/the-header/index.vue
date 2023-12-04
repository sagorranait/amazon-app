<script>
import Notification from './Notification.vue';
import Search from './Search.vue';

  export default {
    components: { Search, Notification }
}
</script>

<template>
  <div class="header h-16 bg-gray-900 flex items-center justify-between px-8">
    <a href="/" class="logo w-1/12 h-16 p-3 flex items-center">
      <img src="https://i.ibb.co/k13rgHw/logo.png" alt="Amazon Logo">
    </a>
    <Search/>
    <Notification/>
  </div>
</template>