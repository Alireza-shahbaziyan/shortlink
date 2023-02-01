<script>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue';
export default{
  components:{
    Header
  }
}
</script>

<template>
  <div class="bg-slate-800">
    <Header/>
    <RouterView/>
  </div>
</template>

