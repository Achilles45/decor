<template>
    <div class="topbar__wrapper container-fluid d-none d-md-block">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <i class="fa fa-home"></i>&nbsp; 22 NDC Road, Beside Police Station, Ozoro, Delta State, Nigeira.
                </div>
                <div class="col-md-3">
                    <i class="fa fa-envelope"></i>&nbsp; hello@primedecor.com
                </div>
                <div class="col-md-3">
                    <i class="fa fa-phone"></i>&nbsp; +2348103515205
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Topbar'
}
</script>
<style lang="scss" scoped>
@import '../styles/colors';
.topbar__wrapper{
    background: $primary-color;
    color: #fff;
    font-size: .83rem;
    padding: .9rem 0;
}
</style>