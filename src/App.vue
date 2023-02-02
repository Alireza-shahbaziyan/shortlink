<script>
import { RouterView } from 'vue-router'
import Header from './components/Header.vue';
import Footer from './views/Footer.vue';
export default{
  components:{
    Header,Footer
  }
}
</script>


<template>
  <div class="bg-slate-800 h-screen flex flex-col justify-between">
    <Header/>
    <RouterView/>
    <Footer/>
  </div>
</template>

