<template>
    <div id="app">
        <AppHeaderLinks />
      <router-view />



    </div>

    <!-- <AppBanner /> -->
    <AppFooter />
  </template>

  <script>
  import AppHeaderLinks from './components/shared/AppHeaderLinks.vue';
  import AppFooter from './components/shared/AppFooter.vue';
//   import AppBanner from './components/shared/AppBanner.vue';
//   import router from './router/index.js';

  export default {
    components: {
      AppHeaderLinks,
      AppFooter,
    //   AppBanner,

    }
  };
  </script>

  <style>
  /* Your global styles */
  </style>
