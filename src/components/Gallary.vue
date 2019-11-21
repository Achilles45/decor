<template>
    <div class="gallery__wrapper container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h4>Gallery</h4>
                    <hr>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4">
                    <img src="../assets/decor-img-1.jpg" class="img-fluid gallery-img" alt="">
                </div>
                 <div class="col-md-4">
                    <img src="../assets/decor-img-2.jpg" class="img-fluid gallery-img" alt="">
                </div>
                 <div class="col-md-4">
                    <img src="../assets/decor-img-3.jpg" class="img-fluid gallery-img" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.gallery__wrapper{
    margin: 3rem 0;
    .gallery-img{
        max-width: 330px;
        height: auto;
        cursor: pointer;
        border-radius: 3px;
    }
}
</style>