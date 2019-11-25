<template>
    <section id="main-container" class="main-container">
      <div class="container">

        <div class="row">
            <div class="col-md-2"></div>
            <div class="col-md-8">

               <h3 class="section-sub-title text-center">We love to hear</h3>
               <br />

               <form id="contact-form" action="contact-form.php" method="post" role="form">
                  <div class="error-container"></div>
                  <div class="row">
                     <div class="col-md-4">
                        <div class="form-group">
                           <label>Name</label>
                        <input class="form-control form-control-name" name="name" id="name" placeholder="" type="text" required>
                        </div>
                     </div>
                     <div class="col-md-4">
                        <div class="form-group">
                           <label>Email</label>
                           <input class="form-control form-control-email" name="email" id="email" 
                           placeholder="" type="email" required>
                        </div>
                     </div>
                     <div class="col-md-4">
                        <div class="form-group">
                           <label>Subject</label>
                           <input class="form-control form-control-subject" name="subject" id="subject" 
                           placeholder="" required>
                        </div>
                     </div>
                  </div>
                  <br/>
                  <div class="form-group">
                     <label>Message</label>
                     <textarea class="form-control form-control-message" name="message" id="message" placeholder="" rows="10" required></textarea>
                  </div>
                  <div class="text-right"><br>
                     <button class="btn btn-primary solid blank" type="submit">Send Message</button> 
                  </div>
               </form>
            </div>
            <div class="col-md-2"></div>
        </div><!-- Content Message row -->
         <br />

        <div class="row">
            <div class="col-md-1"></div>
            <div class="col-md-10">

                <h4 class="section-sub-title text-center">Find Our Location</h4>
                <div class="gap-60"></div>
                <div id="map" class="map"></div>
                <div class="gap-40"></div>

            </div>
            <div class="col-md-1"></div>
        </div><!--/ Map row end -->
        <br />
        <div class="row">
            <div class="col-md-1"></div>
            <div class="col-md-10">
                    <h2 class="section-sub-title text-center">Reaching our Office</h2>
                    <h3 class="section-title text-center">Right here</h3>
                <br />
                    <div class="row">
                    <div class="col-md-4">
                    <div class="ts-service-box-bg text-center">
                        <span class="ts-service-icon icon-round">
                            <i class="fa fa-map-marker"></i>
                        </span>
                        <div class="ts-service-box-content">
                            <h4>Visit Our Office</h4>
                            <p>No 15 Olajuwon street, Lagos</p>
                        </div>
                    </div>
                    </div><!-- Col 1 end -->

                    <div class="col-md-4">
                    <div class="ts-service-box-bg text-center">
                        <span class="ts-service-icon icon-round">
                            <i class="fa fa-envelope"></i>
                        </span>
                        <div class="ts-service-box-content">
                            <h4>Email Us</h4>
                            <p>hello@solabtechnologies.com</p>
                        </div>
                    </div>
                    </div><!-- Col 2 end -->

                    <div class="col-md-4">
                    <div class="ts-service-box-bg text-center">
                        <span class="ts-service-icon icon-round">
                            <i class="fa fa-phone-square"></i>
                        </span>
                        <div class="ts-service-box-content">
                            <h4>Call Us</h4>
                            <p>+234 8183297338</p>
                        </div>
                    </div>
                    </div><!-- Col 3 end -->
                </div>
            </div>
            <div class="col-md-1"></div>
        </div><!-- Office detail end -->
        
         
      </div><!-- Container end -->
   </section><!-- Main container end -->
</template>

<script>
    import '@/assets/js/custom.js'
    import '@/assets/js/gmap3.js'
    
    export default {
        data (){
            return{
            }
        }
    }
</script>

<style>
    .map {
        height: 350px;
        z-index: 1;
    }

    .contact-info-box {
        margin-top: 20px;
    }

    .contact-info-box i {
        float: left;
        font-size: 24px;
        color: #ffb600;
    }

    .contact-info-box-content {
        padding-left: 40px;
    }

    .contact-info-box-content h4 {
        font-size: 16px;
        margin-top: 0;
        line-height: normal;
        font-weight: 700;
    }

    .contact-info-box-content p {
        margin-bottom: 0;
    }

    label {
        font-weight: 400;
    }
    

    h4 {
        font-size: 18px;
        line-height: 28px;
        text-transform: uppercase;
        letter-spacing: -.2px;
    }
    .section-title{
        font-size: 18px;
        line-height: 28px;
        margin:0;
        text-transform: uppercase;
        font-weight: 300;
    }

    .section-sub-title{
        font-weight: 900;
        font-size: 36px;
        line-height: 46px;
        margin: 0 0 45px;
        color: #212121;
}
/* Column title */

.column-title{
    margin: 0 0 40px;
}

.column-title-small{
    font-size: 20px;
    margin: 0 0 25px;
}

.ts-service-box-bg {
    background: #252525;
    color: #fff;
    padding: 30px;
}

h2 {
    font-size: 28px;
    line-height: 36px;
    text-transform: uppercase;
    letter-spacing: -1px;
    color: #000000;
    font-weight: 700;
    font-family: 'Montserrat', sans-serif;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased !important;
}

h3 {
    font-size: 24px;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: -.5px;
    color: #000000;
    font-weight: 700;
    font-family: 'Montserrat', sans-serif;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased !important;
}
                

</style>