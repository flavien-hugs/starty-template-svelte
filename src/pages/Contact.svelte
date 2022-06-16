<script>
	import { Link } from 'svelte-routing'
	import FormContact from '../layouts/FormContact.svelte';

	let src = '/assets/img/about.jpg'
</script>

<section class="bg-half-170 d-table w-100" style="background:url({src}) center;">
	<div class="bg-overlay bg-gradient-overlay"></div>
	<div class="container">
		<div class="row mt-5 justify-content-center">
			<div class="col-12">
				<div class="title-heading text-center">
					<small class="text-white-50 mb-1 fw-medium text-uppercase mx-auto">What we offer?</small>
					<h5 class="heading fw-semibold mb-0 page-heading text-white">Services Agency</h5>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="section pb-0">
	<div class="container">
		<div class="row">
			<div class="col-md-4">
				<div class="card border-0 text-center features feature-clean bg-transparent">
					<div class="icons text-primary text-center mx-auto">
						<i class="uil uil-phone d-block rounded h3 mb-0"></i>
					</div>
					<div class="content mt-3">
						<h5 class="footer-head">Phone</h5>
						<p class="text-muted">Start working with Starty that can provide everything</p>
						<a href="tel:+152534-468-854" class="text-foot">+152 534-468-854</a>
					</div>
				</div>
			</div>

			<div class="col-md-4 mt-4 mt-sm-0 pt-2 pt-sm-0">
				<div class="card border-0 text-center features feature-clean bg-transparent">
					<div class="icons text-primary text-center mx-auto">
						<i class="uil uil-envelope d-block rounded h3 mb-0"></i>
					</div>
					<div class="content mt-3">
						<h5 class="footer-head">Email</h5>
						<p class="text-muted">Start working with Starty that can provide everything</p>
						<a href="mailto:contact@example.com" class="text-foot">contact@example.com</a>
					</div>
				</div>
			</div>

			<div class="col-md-4 mt-4 mt-sm-0 pt-2 pt-sm-0">
				<div class="card border-0 text-center features feature-clean bg-transparent">
					<div class="icons text-primary text-center mx-auto">
						<i class="uil uil-map-marker d-block rounded h3 mb-0"></i>
					</div>
					<div class="content mt-3">
						<h5 class="footer-head">Location</h5>
						<p class="text-muted">C/54 Northwest Freeway, Suite 558, <br>Houston, USA 485</p>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div class="container mt-100 mt-60">
		<div class="row justify-content-center">
			<div class="col-lg-8">
				<div class="section-title mb-5 pb-2 text-center">
					<h4 class="title mb-3">Get In Touch !</h4>
					<p class="text-muted para-desc mx-auto mb-0">Our design projects are fresh and simple and will benefit your business greatly. Learn more about our work!</p>
				</div>
				<div class="custom-form mb-5 mt-5">
					<form method="post" name="myForm" onsubmit="return validateForm()">
						
						<FormContact/>

						<div class="row">
							<div class="col-12">
								<div class="d-grid">
									<button type="submit" id="submit" name="send" class="btn btn-primary">Send Message</button>
								</div>
							</div>
						</div>
					</form>
				</div>
			</div>
		</div>
	</div>
</section>