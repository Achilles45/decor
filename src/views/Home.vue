<template>
  <div class="home">
    <Topbar />
    <Navbar />
  </div>
</template>

<script>
// @ is an alias to /src
import Topbar from '@/components/Topbar.vue';
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'home',
  components:{
    Topbar,
    Navbar
  }
}
</script>
