<template>
    <div class="about__wrapper container-fluid">
        <div class="row">
            <div class="col-md-2"></div>
            <div class="col-md-8 heading text-center">
                <hr>
                <h4>About Us</h4>
                <hr>
                <p>Prime decor is a marketplace aggregator for professional service providers such as cooks, hair stylist, event planners, make-up artist and clients who needs such services within their locality. Professional services providers can now earn more income and clients can find these vetted service providers without breaking the bank easily on one platform.We exist to help provide quality services to our clients. You would want to give us a try today!</p>
            </div>
            <div class="col-md-2"></div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.about__wrapper{
    margin: 5rem 0;
    h4{
        color: #000;
        font-weight: bold;
    }
    p{
        color: #404040;
        font-size: .95rem;
    }
}

//MEDIA QUERIES
@media only screen and (max-width: 1000px) {
  .p{
      font-size: .83rem;
      line-height: 1.3;
  }
}
</style>