<template>
  <!-- COMPANY NAME: FrontEnd Firepower -->
  <!-- SLOGAN: Unleashing the Web's Full Potential with FrontEnd Firepower! -->
  <body>
    <!-- Component calls -->
    <NavBar />
    <!-- <HamburgerOverlay /> -->
    <!-- <ChatBoxCrisp /> -->
    <!-- <ChatBoxGPT /> -->

    <!--  -->

    <!-- Help button -->
    <!-- <button class="help-trigger">
      <span class="iconify" data-icon="fluent:chat-20-regular"></span>
    </button> -->
  </body>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';

import NavBar from '../components/NavBar.vue';
// import HamburgerOverlay from '../components/HamburgerOverlay.vue';
// import ChatBoxCrisp from '../components/ChatBoxCrisp.vue';
// import ChatBoxGPT from '../components/ChatBoxGPT.vue';

export default {
  name: 'IndexPage',

  components: {
    NavBar,
    // HamburgerOverlay,
    // ChatBoxCrisp,
    // ChatBoxGPT,
  },

  // head() {
  //   return {
  //     script: [
  //       {
  //         src: 'https://client.crisp.chat/l.js',
  //         async: true,
  //       },
  //       {
  //         innerHTML: `
  //         window.$crisp=[];
  //         window.CRISP_WEBSITE_ID="27d397b6-b2d8-4ddb-a1c8-f9635c1ba63e";
  //       `,
  //       },
  //     ],
  //   };
  // },
};
</script>

<style>
.help-trigger {
  background-color: #ec6800;
  border-radius: 5em;
  color: white;
}
</style>
