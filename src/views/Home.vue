<template>
  <div class="home">
    <Topbar />
    <Navbar />
    <Banner />
    <Services />
    <About />
    <Process />
    <Ambassador />
    <Footer />
    <!-- <Gallary /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Topbar from '@/components/Topbar.vue';
import Navbar from '@/components/Navbar.vue';
import Banner from '@/components/Banner.vue';
import Services from '@/components/Services.vue';
import About from '@/components/About.vue';
import Process from '@/components/Process.vue';
import Gallary from '@/components/Gallary.vue';
import Ambassador from '@/components/Ambassador.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'home',
  components:{
    Topbar,
    Navbar,
    Banner,
    Services,
    About,
    Process,
    Gallary,
    Ambassador,
    Footer
  }
}
</script>
