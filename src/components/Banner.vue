<template>
    <div class="banner__wrapper container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-10">
                    <h4>Providing you with service providers on the go!</h4>
                    <p>Get access to event planners, painters, hair stylist, photographers, cooks, laundry men, make-up artist, and other service providers in your locality.</p><br>
                    <router-link to="/" class="banner__btn">Get started &nbsp;&nbsp;&nbsp;&nbsp; <i class="fa fa-angle-right animate"></i> </router-link>
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
        text-decoration: none
    }
    .animate{
        animation-name: animate;
        animation-duration: 2s;
        animation-iteration-count: infinite;
        animation-direction: alternate;
    }
}

//Animte css
@keyframes animate{
    from{
        transform: translateX(-30%);
        opacity: 0;
    }
    to{
        transform: translateX(80%);
        opacity: 1;
    }
}

//MEDIA QUERIES
@media only screen and (max-width: 1000px) {
    .banner__wrapper{
        min-height: 510px !important;
        h4{
            font-size: 1.5rem;
        }
        p{
            font-size: .83rem;
            line-height: 1.3;
        }
    }
}
</style>