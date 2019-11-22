<template>
  <div class="about">
    <Navbar />
    <div class="about__wrapper container-fluid mb-5 mt-2">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center">
            <div class="contents">
              <hr>
            <h4>About Us</h4>
            <hr>
            <p>Prime decor is a marketplace aggregator for professional service providers such as cooks, hair stylist, event planners, make-up artist and clients who needs such services within their locality. Professional services providers can now earn more income and clients can find these vetted service providers without breaking the bank easily on one platform.We exist to help provide quality services to our clients. You would want to give us a try today!</p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <h4>What makes us special</h4>
          </div>
        </div>
        <div class="box__wrapper">
            <div class="box">
              <i class="fa fa-comments icons"></i><h6>24/7 Customer Support</h6>
              <p>The customer support team is alsways happy to respond to all your queries in real time</p>
            </div>
             <div class="box">
              <i class="fa fa-check-square icons"></i><h6>Quality Services</h6>
              <p>Our identity has alsways been around offering quality serices to our clients. That is where we function best</p>
            </div>
             <div class="box">
              <i class="fa fa-credit-card icons"></i><h6>Fair Pricing</h6>
              <p>Our pricing of products and services is very fair and truely reflects our belief that you don't need to break the bank for quality</p>
            </div>
          </div>
      </div>
    </div>
    <Footer />
  </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: 'about',
  components:{
    Navbar,
    Footer
  }
}
</script>
<style lang="scss" scoped>
@import '../styles/colors';
.about__wrapper{
  .contents{
    h4{
    font-weight: bold;
    color: #000;
  }
  p{
    color: #404040;
    font-size: .98rem;
    line-height: 1.7;
  }
  }
  .box__wrapper{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 20px;
    margin-top: 1.5rem;
    .box{
      padding: 2rem;
      border-radius: 3px;
      box-shadow: 7px 5px 20px 0 rgba(72,72,121, .15);
      h6{
        padding: .5rem 0;
        font-weight: bold;
        color: #404040
      }
      p{
        color: #404040;
        font-size: .89rem;
      }
      .icons{
        color:$primary-color;
        font-size: 1.3rem;
      }
    }
  }
}
</style>