<template>
  <div>
    <navigation></navigation>
    <Nuxt />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation';
import axios from 'axios';

axios.defaults.headers.common['user-key'] = "some key";
axios.defaults.headers.common['X-Requested-With'] = "XMLHttpRequest";

export default{
  components:{
    Navigation
  }
}

</script>
