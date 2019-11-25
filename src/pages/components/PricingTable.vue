<template>
    <div>
        <!-- Pricing table start -->
            <div id="pricing" class="pricing">
                <div class="container-fluid" >
                    <div class="container-fluid">
                        <div class="row">
                            <div class="col-md-12 heading">
                                <span class="title-icon float-left"><i class="fa fa-university"></i></span>
                                <h2 class="title">Pricing Table <span class="title-desc">Cheapest Pricing Ever</span></h2>
                            </div>
                        </div><!-- Title row end -->
                    </div>
                    <div class="row">
                        <!-- plan start -->
                        <div class="col-md-3 col-sm-6 wow fadeInUp" data-wow-delay=".5s">
                            <div class="plan text-center">
                                <span class="plan-name">Basic <small>Monthly plan</small></span>
                                <p class="plan-price"><sup class="currency">₦</sup><strong>1,999</strong><sub>.99</sub></p>
                                <ul class="list-unstyled">
                                    <li>₦ 2.00  price per unit</li>
                                    <li>1000 SMS Unit Range</li>
                                    <li>50 Bonus Credit</li>
                                    <li>Delivery Report</li>
                                </ul>
                                <router-link class="btn btn-primary" to="/signup"> Sign Up </router-link>
                            </div>
                        </div><!-- plan end -->

                        <!-- plan start -->
                        <div class="col-md-3 col-sm-6 wow fadeInUp" data-wow-delay="1s">
                            <div class="plan text-center">
                                <span class="plan-name">Standard <small>Monthly plan</small></span>
                                <p class="plan-price"><sup class="currency">₦</sup><strong>9,499</strong><sub>.99</sub></p>
                                <ul class="list-unstyled">
                                    <li>₦ 1.90  price per unit</li>
                                    <li>5000 SMS Unit Range</li>
                                    <li>100 Bonus Credit</li>
                                    <li>Delivery Report</li>
                                    <li>24/7 Live Support</li>
                                </ul>
                                <router-link class="btn btn-primary" to="/signup"> Sign Up </router-link>
                            </div>
                        </div><!-- plan end -->

                        <!-- plan start -->
                        <div class="col-md-3 col-sm-6 wow fadeInUp" data-wow-delay="1.4s">
                            <div class="plan text-center featured">
                                <span class="plan-name">Professional <small>Monthly plan</small></span>
                                <p class="plan-price"><sup class="currency">₦</sup><strong>18,499</strong><sub>.99</sub></p>
                                <ul class="list-unstyled">
                                    <li>₦ 1.85  price per unit</li>
                                    <li>10,000 SMS Unit Range</li>
                                    <li>500 Bonus Credit</li>
                                    <li>Delivery Report</li>
                                    <li>SMS Scheduler</li>
                                    <li>24/7 Live Support</li>
                                </ul>
                                <router-link class="btn btn-primary" to="/signup"> Sign Up </router-link>
                            </div>
                        </div><!-- plan end -->

                        <!-- plan start -->
                        <div class="col-md-3 col-sm-6 wow fadeInUp" data-wow-delay="1.6s">
                            <div class="plan text-center">
                                <span class="plan-name">Premium <small>Monthly plan</small></span>
                                <p class="plan-price"><sup class="currency">₦</sup><strong>42,949</strong><sub>.99</sub></p>
                                <ul class="list-unstyled">
                                    <li>₦ 1.80  price per unit</li>
                                    <li>23,000 SMS Unit Range</li>
                                    <li>1000 Bonus Credit</li>
                                    <li>Delivery Report</li>
                                    <li>SMS Scheduler</li>
                                    <li>Customizable Sender</li>
                                    <li>24/7 Live Support</li>
                                </ul>
                                <router-link class="btn btn-primary" to="/signup"> Sign Up </router-link>
                            </div>
                        </div><!-- plan end -->
                    </div>
                    <!--/ Content row end -->
                </div>
                <!--/  Container end-->
            </div>
            <!--/ Pricing table end -->

        </div>
</template>

<script>
    
</script>

<style>
        /* Pricing table
================================================== */
/* Styles from  biscraft common.css */

.btn.btn-primary{
	border: 2px solid #ee3b24;
}

.btn.btn-primary:hover{
	background: #ee3b24;
}

.btn.btn-primary.solid{
	background: #ee3b24;
}

.title{
    position: relative;
    margin-left: 10px;
    line-height: 32px;
    border-left: 2px solid #e7e7e7;
    display: inline-block;
    padding-left: 15px;    
}

.title-desc {
  font-family: 'Lato', serif;
  font-size: 16px;
  line-height: 18px;
  font-weight: 400;
  text-transform: capitalize;
  display: block;
  color: #6A6A6A;
}

.title-icon {
    font-size: 48px;
    margin-right: 15px;
    margin-top: 9px;
    color: #6A6A6A;
    float: none !important;
    margin: 0 0 20px;
    display: inline-block;
  }

.title-icon:hover {
    color: #ee3b24;
  }  

.heading {
    padding-bottom: 50px;
    margin-top: 10px;
    transition: all 0.3s ease 0s;
}

.pricing {
  padding-bottom: 80px;
  margin-left: 60px;
  margin-right: 60px;
  
}

.plan {
  border: 1px solid #dedede;
  
}

.plan-name {
  display: block;
  font-size: 24px;
  line-height: 30px;
  font-weight: 700;
  padding: 20px 0;
  color: #959595;
}

.plan-price {
  font-size: 48px;
  padding: 30px 0;
  margin-bottom: 30px;
  position: relative;
  background: #f2f2f2;
}

.plan-price:after {
  bottom: -30px;
  border: solid transparent;
  content: " ";
  position: absolute;
  border-width: 15px;
  border-top-color: #f2f2f2;
  left: 50%;
  margin-left: -16px;
}

.plan.featured .plan-name {
  color: #323232;
}

.plan.featured .plan-price {
  color: #ffffff;
}

.plan-price .currency {
  top: -0.9em;
  font-size: 50%;
  left: -0.01em;
  font-weight: 700;
}

.plan-name small {
  display: block;
  font-size: 12px;
  font-weight: 700;
  line-height: normal;
}

.plan-price sub {
  font-size: 18px;
  font-weight: 700;
}

.plan ul {
  background: #fff;
  padding: 0;
  margin-bottom: 0;
}

.plan ul li {
  border-top: 1px dashed #dedede;
  padding: 12px 29px;
  font-weight: 500;
}

.plan ul li:first-child {
  border-top: 0 !important;
}

.plan a.btn {
  color: #323232;
  background: #fff;
  margin-top: 25px;
  margin-bottom: -20px;
  padding: 8px 30px;
}

.plan a.btn:hover {
  color: #ffffff;
}

.plan.featured .plan-price{
	background: #ee3b24;
}
.plan.featured .plan-price:after{
	border-top-color: #ee3b24;
}


</style>