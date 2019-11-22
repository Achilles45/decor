<template>
    <footer class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h4>About</h4>
                    <p>Prime decor is a marketplace aggregator that connects professionals in beauty, decor, hair styling, catering and allied services to clients that needs them around their locality.</p>
                </div>
                <div class="col-md-4">
                    <h4>Contact Info</h4>
                    <h6><i class="fa fa-home icons"></i>&nbsp;&nbsp;&nbsp;&nbsp; Head Office</h6>
                    <p>22 NDC Road, Beside Police Station, Ozoro, Delta State, Nigeira.</p>
                    <h6><i class="fa fa-envelope icons"></i>&nbsp;&nbsp;&nbsp;&nbsp; Email Address</h6>
                    <p>hello@primedecor.com</p>
                    <h6><i class="fa fa-phone icons"></i>&nbsp;&nbsp;&nbsp;&nbsp; Phone & Whatsapp</h6>
                    <p>08103515205</p>
                </div>
                <div class="col-md-4">
                    <h4>Connect with us!</h4>
                    <a href="/"><i class="fab fa-facebook"></i></a>
                    <a href="/"><i class="fab fa-instagram"></i></a>
                    <a href="/"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
            <hr>
            <small>Terms and Condition apply. &copy; Copyright 2019. All rights reserved.</small>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
@import '../styles/colors';
footer{
    background: #000;
    color: #fff;
    padding: 6rem 0;
    h4{
        padding-bottom: .5rem;
        font-size: 1.2rem;
    }
    p{
        font-size: .8rem;
        opacity: .7;
    }
    h6{
        padding-top: .5rem;
        opacity: .8;
    }
    .icons{
        color:$primary-color;
    }
    hr{
        background: #fafafa;
        opacity: .7;
    }
    a{
        color:$primary-color;
        font-size: 1.3rem;
        padding-right: 1rem;
    }
}
</style>