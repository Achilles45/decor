<template>
  <div class="home">
    <Topbar />
    <Navbar />
    <Banner />
  </div>
</template>

<script>
// @ is an alias to /src
import Topbar from '@/components/Topbar.vue';
import Navbar from '@/components/Navbar.vue';
import Banner from '@/components/Banner.vue';

export default {
  name: 'home',
  components:{
    Topbar,
    Navbar,
    Banner,
  }
}
</script>
