<template>
    <div class="get-started center wow fadeInDown">
        <h2>Ready to get started</h2>
        <p class="lead">Enjoy amazing offers when you use our services, subscribe to these exclusive plans and reap full benefits with <strong><em>no sweats. </em></strong></p>
        <p class="lead">We provide you the cheapest SMS services prices in Nigeria</p>
       <div class="request">
            <h4><router-link to="/signup">Let's Get Started</router-link></h4>
        </div>
    </div><!--/.get-started-->
</template>

<script>
    
</script>

<style>

.get-started {
  background: none repeat scroll 0 0 #F3F3F3;
  border-radius: 3px;
  padding-bottom: 30px;
  position: relative;
  margin-bottom: 18px;
  margin-top: 60px;
}

.get-started h2 {
  padding-top: 30px;
  margin-bottom: 20px;
}

.center {
  text-align: center;
  padding-bottom: 55px;
}

.center h2{
  font-size: 36px;
  margin-top: 0;
  margin-bottom: 20px;
}

.lead{
  font-size: 16px;
  line-height: 24px;
  font-weight: 400;
}

.request {
  bottom: -30px;
  left: 50%;
  position: absolute;
  margin-left: -110px;
}

.request h4 {
  position: absolute;
  width: 220px;
  position:relative;
}

.request h4 a{
  background:#c52d2f;
  color: #fff;
  font-size: 14px;
  font-weight: normal;
  border-radius: 3px;
  padding: 5px 15px;
}

.request h4:after {
  border-color: #c52d2f transparent transparent;
  border-style: solid;
  border-width: 15px;
  bottom: -12px;
  content: "";
  height: 0;
  position: absolute;
  right: 13px;
  z-index: -99999;
}

.request h4:before {
  border-color: #c52d2f transparent transparent;
  border-style: solid;
  border-width: 15px;
  bottom: -12px;
  content: "";
  height: 0;
  left: 13px;
  position: absolute;
  z-index: -99999;
}

.h2 {
    font-weight: 600;
    font-family: 'Open Sans', sans-serif;
    color: #4e4e4e;
}

</style>