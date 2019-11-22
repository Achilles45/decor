<template>
    <div class="ambassador">
        <Navbar />
        <div class="wrapper">
            <div class="container">
                <div class="row">
                    <div class="form__wrapper">
                        <h5>Create a free account</h5>
                        <small>It's very simple to do!</small>
                        <hr>
                        <form action="">
                            <div class="row">
                                <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="fname">First Name</label>
                                        <input type="text" class="form-control" v-model="fname">
                                    </div>
                                </div>
                                  <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="lname">Last Name</label>
                                        <input type="text" class="form-control" v-model="lname">
                                    </div>
                                </div>
                            </div>
                             <div class="row">
                                <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="email">Email Address</label>
                                        <input type="email" class="form-control" v-model="email">
                                    </div>
                                </div>
                                  <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="phone">Phone Number</label>
                                        <input type="text" class="form-control" v-model="phone">
                                    </div>
                                </div>
                            </div>
                             <div class="row">
                                <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="select">Select skills</label>
                                      <select name="select" id="" v-model="select" class="form-control">
                                          <option value=""></option>
                                          <option value="Interior decor">Interior decor</option>
                                          <option value="Cook">Cook</option>
                                          <option value="Laundry man">Laundry man</option>
                                          <option value="Event planner">Event planner</option>
                                          <option value="Make-up artist">Make-up artist</option>
                                          <option value="Painter">Painter</option>
                                      </select>
                                    </div>
                                </div>
                                  <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="address">Home Address</label>
                                        <input type="text" class="form-control" v-model="address">
                                    </div>
                                </div>
                            </div>
                             <div class="row">
                                <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="password">Password</label>
                                        <input type="password" class="form-control" v-model="password">
                                    </div>
                                </div>
                                  <div class="col-md-6">
                                    <div class="form-group">
                                        <label for="confirm-password">Confirm password</label>
                                        <input type="text" class="form-control" v-model="repeatPassword">
                                    </div>
                                </div>
                            </div>
                            <button type="submit" class="register-btn">Sign Up</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue';
export default {
    name: 'ambassador',
    components:{
        Navbar
    }
}
</script>
<style lang="scss" scoped>
@import '../styles/colors';
.wrapper{
    background: #fafafa;
    height: 100vh;
    .form__wrapper{
        background: #fff;
        margin: 3rem auto;
        max-width: 500px;
        height: auto;
        padding: 1.5rem 2rem;
        border-radius: 2px;
        box-shadow: 7px 5px 30px 0 rgba(72,72,121, .15);
        small{
            font-weight: bold;
            color: #627081;
            
        }
        form{
            margin-top: .6rem;
            input, select{
                border-radius: 2px;
                box-shadow: none;
                font-size: .9rem;
                color: #404040;
                height: 2.8rem;;
            }
            label{
                font-size: .8rem;
                color: #627081;
                font-weight: bold;
            }
            .register-btn{
                background: #000;
                width: 100%;
                color: #fff;
                text-decoration: none;
                border: none;
                padding: .8rem 0;
                font-weight: bold;
                font-size: .89rem;
                border-radius: 2px;
            }
        }
    }
}
</style>