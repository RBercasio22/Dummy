<template>
  <Main />
</template>

<script>
import { defineComponent } from 'vue';

// Components
//import HelloWorld from '../components/HelloWorld.vue';
import Main from '../components/Main.vue';


//  <HelloWorld />
export default defineComponent({
  name: 'HomeView',

  components: {
    Main
    //HelloWorld,
  },
});
</script>
