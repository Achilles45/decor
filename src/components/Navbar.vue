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
}
.fa-bars{
    // background: $primary-color;
    color: $primary-color;
}
}
</style>