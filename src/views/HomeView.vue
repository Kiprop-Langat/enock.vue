<template>
  <div class=" flex items-center justify-center bg-emerald-200">
    <h1></h1>
<Home/>
  
  </div>
</template>

<script>
import Heroes from '@/components/heroes.vue';
import Home from '@/components/home.vue';

// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
    Heroes,
    Home
}
}
</script>
