<template>
<v-app>
  <Navbar/>
</v-app>
</template>

<script>
import Navbar from "./components/Navbar.vue"
export default {
  components:{
    Navbar
    },
  props: {
      source: String,
    },
    data: () => ({
      drawer: null,
    }),
    };
</script>
