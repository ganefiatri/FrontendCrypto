<template>
  <TampilanNavbar></TampilanNavbar>
  <TampilanBody></TampilanBody>
  <TampilanFooter></TampilanFooter>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import './assets/tailwind.css'
import TampilanNavbar from './components/TampilanNavbar.vue'
import TampilanBody from './components/TampilanBody.vue'
import TampilanFooter from './components/TampilanFooter.vue';

export default {
  name: 'App',
  components: {
    TampilanNavbar,
    TampilanBody,
    TampilanFooter
},
};
</script>


