<template>
    <div class="banner__wrapper container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h4>Providing you with service providers on the go!</h4>
                    <p>Get access to event planners, painters, hair stylist, photographers, cooks, laundry men, make-up artist, and other service providers in your locality.</p>
                    <router-link to="/" class="banner__btn">Get started</router-link>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Calistoga&display=swap');
@import '../styles/colors';
.banner__wrapper{
    background: url('../assets/banner.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    min-height: 470px;
    box-shadow: inset 0 0 0 1000px rgba(0,0,0,.85);
    color: #fff;
    h4{
        padding-top: 6rem;
        // font-family: 'Calistoga';
        font-size: 2.2rem;
        line-height: 1.2;
        font-weight: bold;
        padding-bottom: 1.2rem;
    }
    p{
        font-size: .95rem;
        opacity: .7;
        padding-bottom: 1.3rem;
    }
    .banner__btn{
        background: $primary-color;
        color: #fff;
        padding: 1rem 2.5rem;
        border-radius: 3px;
    }
}
</style>