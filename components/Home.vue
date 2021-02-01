<template>
	<div>
		<div class="pb-5" style="position: relative">
			<div class="wrapper">
				<div class="container-fluid">
					<div class="row mx-1 mt-4 mt-md-5">
						<div class="col-md-8 px-0">
							<div class="row mb-4 p-0">
								<div class="col">
									<h3 :class="{ 'content-night-mode': darkMode }"><span class="app-main-color-blue text-default">Building secure financial technology products</span> >> <span class="app-main-color-red">for everyone.</span></h3>
								</div>
							</div>
							<p class="fs-5" :class="{ 'content-night-mode': darkMode }">Financial technology has been changing at a rapid pace. But millions of people around the globe still do not have access to basic financial services.</p>
							<p class="fs-5 mt-4" :class="{ 'content-night-mode': darkMode }">Paytaca wants to bridge this gap as we introduce clever and user-friendly innovations through the safety and security of digital money -- as if you have cash on your hands.</p>
							<div class="row">
								<div class="d-flex justify-content-center justify-content-md-start mt-3 mb-5">
									<a href="#" type="button" class="btn btn-md btn-primary" style="position: relative; z-index: 3">
										<i class="fab fa-google-play fa-lg" style="position: relative; top: -3px;"></i>
										<span style="position: absolute; top: 8px" class="font-sm">GET IT ON</span>
										<span style="margin-top: 10px; display: inline-block">Google Play</span>
									</a>
									<a href="#" type="button" class="btn btn-primary pt-3 ms-3" style="position: relative; z-index: 3">
										<i class="fab fa-apple fa-lg" style="position: relative; top: -4px;"></i>
										<span style="position: absolute; top: 8px" class="font-sm">Download on the</span>
										<span>App Store</span>
									</a>
								</div>
							</div>
						</div>
						<div class="col-md-4 px-0 mb-4">
							<div class="d-flex justify-content-center mt-0 mt-md-2 justify-content-md-end">
								<img src="~/assets/phonedraft2.png" width="60%" class="img-fluid" style="z-index: 1">
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="custom-shape-divider-bottom-1611813748">
			    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
			        <path d="M600,112.77C268.63,112.77,0,65.52,0,7.23V120H1200V7.23C1200,65.52,931.37,112.77,600,112.77Z" class="shape-fill"></path>
			    </svg>
			</div>
		</div>
		<div class="presentation-row">
			<div class="wrapper-presentation">
				<div class="row mx-1 py-4 pt-md-4 pb-md-5">
					<div class="col-md-6 mt-4 mt-md-3">
						<div class="d-flex justify-content-center justify-content-md-start">
							<iframe class="rounded" width="90%" height="300px" src="https://www.youtube.com/embed/YiM9CzpP5xA" title="W3Schools Free Online Web Tutorials"></iframe>
						</div>
					</div>
					<div class="col-md-6">
						<h3 class="text-center mt-4 mt-md-5 text-md-start fw-bolder text-light">A wireframe is a simple presentation of a website</h3>
						<p class="fs-6 mt-4 text-light">A wireframe is a simple presentation of a website. It is especially useful during a product’s early stages as it conveys your design ideas</p>
					</div>
				</div>
			</div>
		</div>
		<div class="wrapper" id="features">
			<div class="container">
				<div class="row mx-1 py-5">
					<div class="col">
						<h2 class="text-center fw-bolder mb-5" :class="{ 'content-night-mode-2': darkMode }">Features</h2>
						<div class="d-flex mt-0 mt-md-2 flex-padding px-5">
							<div class="wrapper-feature">
								<img src="~/assets/phonedraft2.png" class="img-fluid" width="100%" alt="Features">
								<div class="card card-feature-tl">
									<div class="card-body feature-body">
										<h2 class="fw-bolder feature-title">Trend Design</h2>
										<p class="mb-0 feature-paragraph">A wireframe is a simple presentation of a website. It is especially useful during</p>
									</div>
								</div>
								<div class="card card-feature-bl">
									<div class="card-body feature-body">
										<h2 class="fw-bolder feature-title">Pixel Perfect</h2>
										<p class="mb-0 feature-paragraph">A wireframe is a simple presentation of a website. It is especially useful during</p>
									</div>
								</div>
								<div class="card card-feature-tr">
									<div class="card-body feature-body">
										<h2 class="fw-bolder feature-title">Design System</h2>
										<p class="mb-0 feature-paragraph">A wireframe is a simple presentation of a website. It is especially useful during</p>
									</div>
								</div>
								<div class="card card-feature-br">
									<div class="card-body feature-body">
										<h2 class="fw-bolder feature-title">Easy to Use</h2>
										<p class="mb-0 feature-paragraph">A wireframe is a simple presentation of a website. It is especially useful during</p>
									</div>
								</div>
							</div>
							<!-- <img src="~/assets/appfeatures.png" class="img-fluid" width="100%" alt="Features"> -->
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="presentation-row mt-2" id="ecosystem">
			<div class="wrapper-presentation">
				<div class="container-fluid">
					<div class="row pt-5">
						<div class="col-12">
							<h2 class="fw-bolder text-light text-center mb-4">Ecosystem</h2>
						</div>
					</div>
					<div class="row py-4 px-4">
						<div class="col-12 col-sm-4">
							<div class="card bg-transparent border-0 mb-2">
								<img src="/blankimage.jpg" class="card-img-top rounded" alt="...">
								<div class="card-body">
									<h5 class="card-title text-light">Card title</h5>
									<p class="card-text text-light">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-4">
							<div class="card bg-transparent border-0 mb-2">
								<img src="/blankimage.jpg" class="card-img-top rounded" alt="...">
								<div class="card-body">
									<h5 class="card-title text-light">Card title</h5>
									<p class="card-text text-light">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-4">
							<div class="card bg-transparent border-0 mb-2">
								<img src="/blankimage.jpg" class="card-img-top rounded" alt="...">
								<div class="card-body">
									<h5 class="card-title text-light">Card title</h5>
									<p class="card-text text-light">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="wrapper" id="faq">
			<div class="container-fluid">
				<div class="row mx-1 pt-5">
					<div class="col-12">
						<h2 class="text-center fw-bolder mb-5" :class="{ 'content-night-mode-2': darkMode }">Frequently Asked Questions</h2>
					</div>
				</div>
				<div class="row pb-5">

					<div class="accordion" id="accordionExample">
					  <div class="accordion-item">
					    <h2 class="accordion-header" id="headingOne">
					      <button class="accordion-button btn-toggle-faq app-main-background-color-red text-light collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
					        Accordion Item #1
					      </button>
					    </h2>
					    <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
					      <div class="accordion-body" :class="{ 'content-night-mode': darkMode }">
					        <strong>This is the first item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
					      </div>
					    </div>
					  </div>
					  <div class="accordion-item">
					    <h2 class="accordion-header" id="headingTwo">
					      <button class="accordion-button btn-toggle-faq app-main-background-color-red text-light collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
					        Accordion Item #2
					      </button>
					    </h2>
					    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
					      <div class="accordion-body" :class="{ 'content-night-mode': darkMode }">
					        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
					      </div>
					    </div>
					  </div>
					  <div class="accordion-item">
					    <h2 class="accordion-header" id="headingThree">
					      <button class="accordion-button btn-toggle-faq app-main-background-color-red text-light collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
					        Accordion Item #3
					      </button>
					    </h2>
					    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
					      <div class="accordion-body" :class="{ 'content-night-mode': darkMode }">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</div>
					    </div>
					  </div>
					</div>

				</div>
			</div>
		</div>
		<div class="presentation-row mt-2" id="team">
			<div class="wrapper-presentation">
				<div class="container-fluid">
					<div class="row pt-5">
						<div class="col-12">
							<h2 class="fw-bolder text-light text-center">Meet Our Team</h2>
							<p class="fs-6 text-light text-center mb-4">With over 10 years of combined experience, we've got a well-seasoned team at the helm.</p>
						</div>
					</div>
					<div class="row py-4 px-4">
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role/Status.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role/Status.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role/Status.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role.</p>
								</div>
							</div>
						</div>
						<div class="col-12 col-sm-3">
							<div class="card bg-transparent border-0 mb-2">
								<div class="d-flex justify-content-center">
									<img src="/software_developer.jpg" class="card-img-top rounded" alt="..." style="width: 84%">
								</div>
								<div class="card-body px-4">
									<h5 class="card-title text-light">Person's Name</h5>
									<p class="card-text text-light">Role.</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="wrapper">
			<div class="container-fluid">
				<div class="row mx-1 py-5">
					<div class="col-12">
						<div class="d-flex justify-content-center">
							<div class="card app-main-background-color-red" style="width: 100%">
							  <div class="card-body">
							  	<h5 class="card-title text-center text-light">Join our waitlist</h5>
							  	<form>
							  		<div class="input-group my-3">
										<input type="email" class="form-control" placeholder="Enter your email" aria-label="Enter your email" aria-describedby="button-email">
										<button class="btn btn-outline-light btn-join-waitlist" type="button" id="button-email"><i class="fas fa-arrow-right"></i></button>
									</div>
							  	</form>
							  </div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="presentation-row-getintouch" style="position: relative;" id="contact">
			<div class="wrapper-presentation" >
				<div class="container-fluid" style="z-index: 3">
					<div class="row mx-1 pt-5 pb-4">
						<div class="col">
							<h2 class="text-center text-light fw-bolder">Get in Touch</h2>
							<p class="fs-6 text-center text-light">Please fill out the quick form and we will be in touch with you.</p>
						</div>
					</div>
				</div>
				<div class="custom-shape-divider-bottom-1611820489">
				    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
				        <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
				        <path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
				        <path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
				    </svg>
				</div>
			</div>
		</div>
		<div class="wrapper">
			<div class="container-fluid">
				<div class="row mx-1 pt-5 pb-4">
					<div class="col-12 col-md-6 pb-5 pb-md-0">
						<form>
							<h4 :class="{ 'content-night-mode-2': darkMode }">Send a messages</h4>
							<div class="mb-3">
							  <input type="text" class="form-control" id="username" placeholder="Username">
							</div>
							<div class="mb-3">
							  <input type="email" class="form-control" id="emailAdd" placeholder="E-mail address">
							</div>
							<div class="mb-3">
							  <textarea class="form-control" placeholder="Message" id="exampleFormControlTextarea1" rows="3"></textarea>
							</div>
							<div class="d-flex justify-content-md-end">
								<button type="submit" class="btn btn-primary">Submit <i class="fas fa-arrow-right fa-sm"></i></button>
							</div>
						</form>
					</div>
					<div class="col-12 col-md-6 ps-md-5" :class="{ 'content-night-mode': darkMode }">
						<h4>Information</h4>
						<p class="fs-6 fw-bold mb-0 mt-3">Corporate Headquarters:</p>
						<p class="fs-6 mb-0">756 Livingston Street, Brooklyn, NY 11201</p>
						<p class="fs-6 mb-0">Phone: +1 (123) 456-7890</p>
						<p class="fs-6 mb-0">Fax: 123-456-7890</p>
						<p class="fs-6 mb-0">Email: info@example.com</p>
						<p class="fs-6 fw-bold mb-0 mt-3">Development Center:</p>
						<p class="fs-6 mb-0">1025 Thomas Jefferson Street NW</p>
						<p class="fs-6 mb-0">Suite 700 West</p>
						<p class="fs-6 mb-0">Washington, DC 20007</p>
						<p class="fs-6 fw-bold mb-0 mt-3">Follow Us</p>
						<div class="mb-3 social-brand">
							<a href="#"><i class="fab fa-instagram fa-sm" :class="{ 'content-night-mode-2': darkMode }"></i></a>
							<a href="#"><i class="fab fa-facebook fa-sm" :class="{ 'content-night-mode-2': darkMode }"></i></a>
							<a href="#"><i class="fab fa-github fa-sm" :class="{ 'content-night-mode-2': darkMode }"></i></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="presentation-row mt-2">
			<div class="wrapper-presentation-footer">
				<div class="container-fluid">
					<div class="row mx-1 pt-4 pb-3">
						<div class="col-md-4">
							<img src="/paytaca_dark_mode.svg" class="mb-2" width="90">
							<p class="text-light fs-7 mb-1 fw-lighter">A wireframe is a simple presentation of a website.</p>
							<div class="mb-3 social-brand">
								<a href="#"><i class="fab fa-instagram fa-sm text-light"></i></a>
								<a href="#"><i class="fab fa-facebook fa-sm text-light"></i></a>
								<a href="#"><i class="fab fa-github fa-sm text-light"></i></a>
							</div>
						</div>
						<div class="col-md-3 ps-md-3 mb-3">
							<p class="text-light my-0 fs-7 fw-bold">Sent Mail</p>
							<p class="text-light my-1 fs-7 fw-lighter">info@example.com</p>
							<p class="text-light my-1 fs-7 fw-lighter">support@example.com</p>
						</div>
						<div class="col-md-3 ps-md-3 mb-3">
							<p class="text-light my-0 fs-7 fw-bold">Make Call</p>
							<p class="text-light my-1 fs-7 fw-lighter">+1 (123) 456-7890</p>
							<p class="text-light my-1 fs-7 fw-lighter">+1 (987) 654-3210</p>
						</div>
						<div class="col-md-2 ps-md-3">
							<p class="text-light my-0 fs-7 fw-bold">Get in Touch</p>
							<p class="text-light my-1 fs-7 fw-lighter">756 Livingston Street,</p>
							<p class="text-light my-1 fs-7 fw-lighter">Brooklyn, NY 11201</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<a class="btn btn-primary rounded-circle btn-back-top pt-2" id="btn-back-top" href="#navbar"><i class="fas fa-chevron-up"></i></a>
	</div>
</template>


<script>

export default {
	props: ['darkMode'],
	data () {
		return {
		}
	},
	watch: {
		darkMode: function(newVal, oldVal) {
			this.changeBodyMode()
        }
	},
	methods: {
		handleScroll () {
	    	var el = document.getElementById('btn-back-top')
		    window.scrollY > 658 ? el.classList.add("btn-back-top-show") : el.classList.remove("btn-back-top-show")
		    window.scrollY < 658 ? el.classList.add("btn-back-top-hide") : el.classList.remove("btn-back-top-hide")
		},
		changeBodyMode () {
			document.body.style.backgroundColor = this.darkMode ? '#2d3748' : ''
		}
	},
	beforeMount () {
		window.addEventListener('scroll', this.handleScroll);
	},
	beforeDestroy() {
		window.removeEventListener('scroll', this.handleScroll);
	}
}
</script>