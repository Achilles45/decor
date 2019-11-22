<template>
<div class="contact">
    <Navbar />
    <div class="contact__wrapper container-fluid">
        <div class="containerr">
            <div class="row">
                <div class="col-12 contact__content mt-5">
                    <h4>Reach out to us</h4>
                    <small>Our customer support team is always on ground to respond to all your queries!</small><br><br>
                    <h6><i class="fa fa-home icons"></i>&nbsp;&nbsp;&nbsp; Office Address</h6>
                    <p>No 90 NDC Road, Beside Police Station, Ozoro, Delta State, Nigeria</p><br>
                    <h6><i class="fa fa-envelope icons"></i>&nbsp;&nbsp;&nbsp; Email Address</h6>
                    <p>hello@primedecor.com</p><br>
                    <h6><i class="fa fa-phone icons"></i>&nbsp;&nbsp;&nbsp; Phone & Whatsapp</h6>
                    <p>+2348103515205</p>
                </div>
            </div>
        </div>
    </div>
    <!-- <Footer /> -->
</div>
</template>
<script>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';
export default {
    name: 'Contact',
    components:{
        Navbar,
        Footer
    }
}
</script>
<style lang="scss" scoped>
@import '../styles/colors';
.contact__wrapper{
    background: #fafafa;
    height: 100vh;
    .contact__content{
        box-shadow: 7px 5px 30px 0 rgba(72,72,121, .15);
        background: #fff;
        border-radius: 3px;
        min-height: 420px;
        padding: 2rem;
        small{
            color: #404040;
            font-weight: bold;
            padding-bottom: 10rem !important;
        }
        .icons{
             font-size: 1.1rem !important;
             color: $primary-color;
        }
        h6{
            font-weight: normal;
            color:#000;
        }
        p{
            font-size: .85rem;
            color: #404040;
        }
    }
    .containerr{
        margin: 0 2rem;
    }
}
</style>