<template>
    <div class="ambassador container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <img src="../assets/girl.png" class="img-fluid girl" alt="">
                </div>
                <div class="col-md-6 content">
                    <h4>Earn more than you currently do by providing your services to more clients!</h4>
                    <p>We'll help you reach more potntial clients that needs your services faster and cost effective if you become an ambassador.</p>
                    <router-link to="/" class="ambassador__btn">Register Now &nbsp;&nbsp; <i class="fa fa-angle-right animate"></i></router-link>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@import '../styles/colors';
.ambassador{
    margin: 3rem 0;
    .girl{
        max-width: 380px;
        height: auto;
        padding-left: 1rem;
    }
   .content{
       padding-top: 5rem;
        h4{
        padding-bottom: 1rem;
        font-weight: bold;
        color: #000;
    }
    p{
        color:#404040;
        padding-bottom: 1rem;
    }
    .ambassador__btn{
        background: #000;
        text-decoration: none;
        padding: 1.2rem 3rem;
        border-radius: 3px;
        color: #fff;
        font-size: .9rem;
       .animate{
        animation-name: animate;
        animation-duration: 2s;
        animation-iteration-count: infinite;
        animation-direction: alternate;
    }
    }
     .ambassador__btn:hover{
            background: $primary-color;
            transition: all ease-in .5s;
        }
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
@media only screen and (max-width: 1000px){
    .girl{
        padding-left: 0rem !important;
        max-width: 310px !important;
    }
    .content{
        padding-top: 1.5rem !important;
    }
}
</style>