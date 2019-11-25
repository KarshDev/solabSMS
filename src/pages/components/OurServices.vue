<template>
    <section id="feature" class="transparent-bg">
        <div class="container">
            <div class="center wow fadeInDown">
                <h2>Our Services</h2>
                <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut <br> et dolore magna aliqua. Ut enim ad minim veniam</p>
            </div>

            <div class="row">
                <div class="features">
                    <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                        <div class="feature-wrap">
                                <i class="fa fa-bullhorn"></i>
                                <h2>Fresh and Clean</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                        </div>
                    </div><!--/.col-md-4-->

                        <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                            <div class="feature-wrap">
                                <i class="fa fa-comments"></i>
                                <h2>Retina ready</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                            </div>
                        </div><!--/.col-md-4-->

                        <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                            <div class="feature-wrap">
                                <i class="fa fa-cloud-download"></i>
                                <h2>Easy to customize</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                            </div>
                        </div><!--/.col-md-4-->
                    
                        <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                            <div class="feature-wrap">
                                <i class="fa fa-leaf"></i>
                                <h2>Adipisicing elit</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                            </div>
                        </div><!--/.col-md-4-->

                        <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                            <div class="feature-wrap">
                                <i class="fa fa-cogs"></i>
                                <h2>Sed do eiusmod</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                            </div>
                        </div><!--/.col-md-4-->

                        <div class="col-md-4 col-sm-6 wow fadeInDown" data-wow-duration="1000ms" data-wow-delay="600ms">
                            <div class="feature-wrap">
                                <i class="fa fa-heart"></i>
                                <h2>Labore et dolore</h2>
                                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h3>
                            </div>
                        </div><!--/.col-md-4-->
                </div><!--/.services-->
            </div><!--/.row-->
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style>

#feature {
  background: #f2f2f2;
  padding-bottom: 40px;
}

.features{
  padding: 0;
}

.feature-wrap {
  margin-bottom: 35px;
  overflow: hidden;
}

.feature-wrap h2{
  margin-top: 10px;
}

.feature-wrap .pull-left {
  margin-right: 25px;
}

.feature-wrap i{
  font-size: 48px;
  height: 110px;
  width: 110px;
  margin: 3px;
  border-radius: 100%;
  line-height: 110px;
  text-align:center;
  background: #ffffff;
  color: #c52d2f;
  border: 3px solid #ffffff;
  box-shadow: inset 0 0 0 5px #f2f2f2;
  -webkit-box-shadow: inset 0 0 0 5px #f2f2f2;
  -webkit-transition: 500ms;
  -moz-transition: 500ms;
  -o-transition: 500ms;
  transition: 500ms;
  float: left;
  margin-right: 25px;
}

.feature-wrap i:hover {
  background: #c52d2f;
  color: #fff;
  box-shadow: inset 0 0 0 5px #c52d2f;
  -webkit-box-shadow: inset 0 0 0 5px #c52d2f;
  border: 3px solid #c52d2f;
}

.transparent-bg {
  background-color: transparent !important;
  margin-bottom: 0;
}

.center h2{
  font-size: 36px;
  margin-top: 0;
  margin-bottom: 20px;
}

.center {
  text-align: center;
  padding-bottom: 55px;
}

.lead{
  font-size: 16px;
  line-height: 24px;
  font-weight: 400;
}
h2{
  font-size: 20px;
  background: #fff;
  font-family: 'Open Sans', sans-serif;
  color:#4e4e4e;
  line-height: 22px;
}

</style>