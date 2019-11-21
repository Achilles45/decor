<template>
    <div class="services container-fluid">
      <div class="intro">
           <h4>What service are you looking for?</h4>
       <p>You can find verified and vetted professionals in catering, beauty & make-over, decorations, photography and others...</p>
      </div>
      <div class="container">
          <div class="row pt-1">
              <div class="col-md-3">
                  <div class="card__wrapper">
                      <img src="../assets/catering.jpeg" class="img img-fluid" alt="">
                     <div class="card__content">
                         <p>Catering services</p>
                         <a href="tel:+2348103515205" class="service__btn">Find Now</a>
                     </div>
                  </div>
              </div>
              <div class="col-md-3">
                  <div class="card__wrapper">
                      <img src="../assets/interior.jpeg" class="img img-fluid" alt="">
                     <div class="card__content">
                         <p>Interior decor</p>
                         <a href="tel:+2348103515205" class="service__btn">Find Now</a>
                     </div>
                  </div>
              </div>
              <div class="col-md-3">
                  <div class="card__wrapper">
                      <img src="../assets/makeup.jpeg" class="img img-fluid" alt="">
                     <div class="card__content">
                         <p>Make-over services</p>
                         <a href="tel:+2348103515205" class="service__btn">Find Now</a>
                     </div>
                  </div>
              </div>
              <div class="col-md-3">
                  <div class="card__wrapper">
                      <img src="../assets/hair.jpeg" class="img img-fluid" alt="">
                     <div class="card__content">
                         <p>Hair styling</p>
                         <a href="tel:+2348103515205" class="service__btn">Find Now</a>
                     </div>
                  </div>
              </div>
          </div>
          <div class="row mt-5">
              <div class="col-md-3"></div>
              <div class="col-md-6 text-center">
                  <h3 class="pb-4"> Can't find the service you want?</h3>
                    <a href="tel:+2348103515205" class="call__btn"><i class="fa fa-phone"></i>&nbsp; &nbsp; Call us now</a>
              </div>
              <div class="col-md-3"></div>
          </div>
      </div>
    </div>
</template>
<style lang="scss" scoped>
@import '../styles/colors';
.services{
    padding: 2rem 0;
    .intro{
        padding-left: 2rem;
        h4{
            color: #000;
            font-weight: bold;
        }
        p{
            color:#404040;
        }
    }
    .card__wrapper{
        box-shadow: 3px 1px 3px rgba(0,0,0,.20);
        border-radius: 3px;
         .img{
                cursor: pointer;
            }
            .img:hover{
                animation-name: animate;  
                animation-duration: 1.5s;
                animation-direction: alternate;
                animation-iteration-count: infinite;
               }
        .card__content{
            padding: 1.1rem 1rem;
            p{
                color: #000;
                font-weight: bold;
                opacity: .8;
            }
            .service__btn{
                background: $primary-color;
                color: #fff;
                font-size: .78rem;
                padding: .7rem 1rem;
                border-radius: 3px;
                text-decoration: none;
            }
        }
    }
    .call__btn{
        background: #000;
        color: #fff;
        font-size: .9rem;
        padding: 1.2rem 2.5rem;
        border-radius: 3px;
        text-decoration: none;
    }
    .call__btn:hover{
            background: $primary-color;
            transition: all ease-in .5s;
        }
}

@keyframes animate{
    from{
        transform: scale(.9)
    }
    to{
        transform: scale(1)
    }
}
</style>