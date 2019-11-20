<template>
  <div class="home">
    <Topbar />
    <Navbar />
    <Banner />
    <About />
  </div>
</template>

<script>
// @ is an alias to /src
import Topbar from '@/components/Topbar.vue';
import Navbar from '@/components/Navbar.vue';
import Banner from '@/components/Banner.vue';
import About from '@/components/About.vue';

export default {
  name: 'home',
  components:{
    Topbar,
    Navbar,
    Banner,
    About
  }
}
</script>
