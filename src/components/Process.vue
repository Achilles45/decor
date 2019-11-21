<template>
    <div class="process__wrapper container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-3"></div>
                <div class="col-md-6 text-center heading">
                    <h4 class="heading">How it works</h4>
                    <p>Finding a service man is very simple and straigh forward</p>
                </div>
                <div class="col-md-3"></div>
            </div>
            <div class="process__grid">
                <div class="process__card">
                   <h6><i class="fa fa-search card__icons"></i>Search</h6>
                   <p>Quickly browse through the service section to see if the service you are looking for is being offerend on the platform & call to get extimate.</p>
                </div>
                 <div class="process__card">
                   <h6><i class="fa fa-credit-card card__icons"></i>Pay deposit</h6>
                   <p>Deposit some percentage of the total cost of the work while the work gets underway.</p>
                </div>
                 <div class="process__card">
                   <h6><i class="fa fa-check-square card__icons"></i>Finish</h6>
                   <p>Pay the remaining balance of the work once the work has been completed.</p>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@import '../styles/_colors';
.process__wrapper{
    background: #F6F7FF;
    padding: 3.5rem 0;
    .heading{
        color: #000;
        font-weight: bold;
        p{
            color:#404040;
            font-weight: normal;
            font-size: .95rem;
        }
    }
    .process__grid{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        grid-gap: 20px;
        margin-top: 1.5rem;
        margin-bottom: 1rem;
        .process__card{
            background: #fff;
            border-radius: 3px;
            padding: 3rem 2rem;
            box-shadow: 7px 5px 30px 0 rgba(72,72,121, .15);
            .card__icons{
                color: $primary-color;
                margin-right: 2rem;
                font-size: 1.2rem;
            }
            h6{
                color: $primary-color;
                padding-bottom: 1rem;
                font-weight: bold;
            }
            p{
                color: #404040;
                font-size: .9rem;
            }
        }
    }
}
</style>