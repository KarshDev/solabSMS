<template>
    <footer id="footer" class="footer bg-overlay">
			<div class="footer-main">
					<div class="row">
						<div class="col-md-4 col-sm-12 footer-widget footer-about">
                            <br />
							<h3 class="widget-title">Do you know that at</h3>
							<img class="footer-logo" src="../assets/img/solablogosmall.png" alt="" />
							<p>We are a technology company committed to developing solutions solving problems facing organisations and communities in Africa.</p>
							<p>We build products to solve problems and create Value.</p>
							<p> We guarantee rapid, reliable, and robust technology solutions that works.</p>

                            <div class="footer-social text-center col-md-12 col-lg-8">
                                <a 
                                    target="_blank" 
                                    href="#" 
                                    rel="tooltip" 
                                    title="Follow us" 
                                    class="btn btn-neutral btn-icon btn-twitter btn-round btn-lg">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a 
                                    target="_blank" 
                                    href="#" 
                                    rel="tooltip" 
                                    title="Like us" 
                                    class="btn btn-neutral btn-icon btn-facebook btn-round btn-lg">
                                    <i class="fab fa-facebook-square"></i>
                                </a>
                                <a 
                                    target="_blank" 
                                    href="#" 
                                    rel="tooltip" 
                                    title="Follow us" 
                                    class="btn btn-neutral btn-icon btn-linkedin btn-lg btn-round">
                                    <i class="fab fa-linkedin"></i>
                                </a>
                                <a 
                                    target="_blank" 
                                    href="#" 
                                    rel="tooltip" 
                                    title="Star on Github" 
                                    class="btn btn-neutral btn-icon btn-github btn-round btn-lg">
                                    <i class="fab fa-github"></i>
                                </a>
                            </div><!-- Footer social end -->

						</div><!-- Col end -->

						<div class="col-md-4 col-sm-12 footer-widget">
                            <br />
							<h3 class="widget-title">Our Services: A few amongst others</h3>
							<ul class="list-arrow">
								<li><a href="#">Web Development</a></li> <br/>
								<li><a href="#">Mobile App Development</a></li><br/>
								<li><a href="#">Computer Application</a></li><br/>
								<li><a href="#">I.T Development and Consultancy</a></li>
							</ul>
							<br />
							<h3 class="widget-title">Contact Details</h3>
							<div class="contact-details">
								<p>Contact us if you have an emergency, with our Hotline and Contact form.</p>
								Email: <span class="text-right">hello@solabtechnologies.com</span>
								<br> Phone Number: <span class="text-right">+234 8183297338</span>
								<br> Location: <span class="text-right"> No 15 Olajuwon street, Yaba, Nigeria</span>
							</div>
						</div><!-- Col end -->

						<div class="col-md-4 col-sm-12 footer-widget">
                            <br />
							<h2 class="widget-title">Contact Form</h2>
                            <div class="form-msg">
								<form>
									<div class="form-group">
										<label for="Name">Name</label>
										<input type="text" class="form-control" id="username" aria-describedby="nameHelp" placeholder="Please, enter your name" required>
									</div>
									<div class="form-group">
										<label for="phoneNumber">Phone Number</label>
										<input type="number" class="form-control" id="phoneNumber" placeholder="Please enter your phone number" required>
									</div>
									<div class="form-group">
										<textarea name="comment" required> Please Enter Your Message </textarea>
									</div>
									<button type="submit" class="btn btn-primary">Send message</button>
								</form>

							</div>
						</div><!-- Col end -->
					</div><!-- Row end -->
			</div><!-- Footer main end -->
	</footer><!-- Footer end -->
</template>

<script>
export default {
  data() {
    return {

    };
  }
};
</script>
<style scoped>

/*- Footer common */

.footer {
    background-color: #0d0d0d;
    color: #999;
}


.footer-main {
    padding: 80px 0 60px;
	margin-left: 60px;
	margin-right: 60px;
}

.footer .widget-title {
    font-size: 16px;
    font-weight: 700;
    position: relative;
    margin: 0 0 30px;
    padding-left: 15px;
    text-transform: uppercase;
    color: #fff;
    border-left: 3px solid #ffb600;
}




/* Footer about us */

.footer-logo {
    margin-bottom: 25px;
}


/* Footer social */

.footer-social {
    margin-top: 15px;
}

.footer-social .widget-title {
    font-size: 14px;
    margin-bottom: 10px;
}

.footer-social ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

.footer-social ul li {
    margin: 0 10px 0 0;
    display: inline-block;
}

.footer-social ul li a i {
    display: block;
    font-size: 18px;
    color: #999;
    background: none;
    -webkit-transition: 400ms;
    -moz-transition: 400ms;
    -o-transition: 400ms;
    transition: 400ms;
}

.footer-social ul li a i:hover {
    color: #fff;
}




/* Links */

.footer-widget ul.list-arrow li {
    border-bottom: 1px solid rgba(255, 255, 255, .07);
    padding: 10px 0;
}

.footer-widget ul.list-arrow li:last-child {
    border-bottom: 0px;
}

.footer-widget ul.list-arrow li a,
.footer-widget ul.list-arrow li:before {
    color: #b4b3b3;
}

.footer-widget ul.list-arrow li:hover a,
.footer-widget ul.list-arrow li:hover {
    color: #ffb600;
}

.contact-details {
    padding-right: 0px;
}

.contact-details .text-right {
    float: right;
}


.footer-menu {
    float: right;
}

.footer-menu ul li {
    display: inline-block;
    line-height: 12px;
    padding-left: 15px;
}

.footer-menu ul.nav li a {
    background: none;
    color: #111;
    padding: 0;
}

.footer-menu ul li a:hover {
    color: #fff;
}

form{
    border-radius: 10px;
    background-color: #111;
    padding: 40px;
}
input{
    width: 100%;
    padding: 10px 10px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ffb600;
    border-radius: 4px;
    box-sizing: border-box;
}
textarea{
   width: 100%;
    padding: 10px 10px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ffb600;
    border-radius: 4px;
    box-sizing: border-box; 
	background-color: lavenderblush;
}
button:hover {
  background-color: #f88f2c;
  display: inline-block;
}

</style>