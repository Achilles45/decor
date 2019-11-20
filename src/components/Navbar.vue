<template>
    <div class="navbar__wrapper container-fluid">
        <div class="container">
            <nav class="navbar navbar-expand-lg">
                <router-link to="/" class="logo"><img src="../assets/logo.png" alt=""></router-link>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <i class="fa fa-bars"></i>
                    </button>

                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav mr-auto">
                            <li class="nav-item active">
                               <router-link to="/" class="nav-link">Home</router-link>
                            </li>
                            <li class="nav-item">
                                <router-link to="/" class="nav-link">About</router-link>
                            </li>
                             <li class="nav-item">
                                <router-link to="/" class="nav-link">Decor shop</router-link>
                            </li>
                             <li class="nav-item">
                                <router-link to="/" class="nav-link">Services</router-link>
                            </li>
                             <li class="nav-item">
                                <router-link to="/" class="nav-link">Become an ambassador</router-link>
                            </li>
                            <li class="nav-item">
                                <router-link to="/" class="nav-link">Login</router-link>
                            </li>
                             <li class="nav-item">
                                <router-link to="/" class="nav-link">Contact</router-link>
                            </li>
                            </ul>
                        </div>
                    </nav>
                            </div>
                        </div>
</template>
<script>
export default {
    data(){

    },
    mounted(){
        this.fixNav();
    },
    methods:{
        fixNav:function(e){
            const nav = document.querySelector('.navbar__wrapper');
            window.onscroll = ()=>{
                if(pageYOffset > 50){
                    nav.classList.add('fixnav');
                }else{
                    nav.classList.remove('fixnav');
                }
            }
        }
    }
}
</script>
<style lang="scss" scoped>
@import '../styles/colors';
.navbar__wrapper{
    padding: 1rem 0;
    .nav-link{
    color: #627081;
    font-weight: bold;
    text-transform: uppercase;
    font-size: .8rem;
    margin-right: .7rem;
    transition: all ease-in-out .5s;
}
.nav-link:hover{
        color: $primary-color !important;
    }
.fa-bars{
    // background: $primary-color;
    color: $primary-color;
}
}
.fixnav{
    position: fixed;
    top:0;
    box-shadow: 30px 0px 5px rgba(0,0,0,.10);
    background: #fff;
    z-index: 1000;
}
//MEDIA QUERIES
@media only screen and (max-width: 1000px) {
  .logo{
      height: auto;
      max-width: 30px !important;
  }
}
</style>