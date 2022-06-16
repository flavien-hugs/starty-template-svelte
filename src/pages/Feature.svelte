<script>
	import { Link } from 'svelte-routing'
	let src = '/assets/img/services.jpg'
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

<section class="section">
	<div class="container">
		<div class="row">
			<div class="col-lg-4 col-md-6">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-circle-layer icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">Pixel Perfect Design</Link>

						<p class="text-muted mb-0 mt-3">
						This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>

			<div class="col-lg-4 col-md-6 mt-4 pt-4 mt-sm-0 pt-sm-0">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-window-grid icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">Unlimited Layouts</Link>

						<p class="text-muted mb-0 mt-3">This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>

			<div class="col-lg-4 col-md-6 mt-4 pt-4 mt-lg-0 pt-lg-0">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-shopping-cart icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">Online Shopping</Link>

						<p class="text-muted mb-0 mt-3">This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>
			<div class="col-lg-4 col-md-6 mt-4 pt-4">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-award-alt icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">Simple and Secure</Link>

						<p class="text-muted mb-0 mt-3">This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>

			<div class="col-lg-4 col-md-6 mt-4 pt-4">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-thumbs-up icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">Automatic Updates</Link>

						<p class="text-muted mb-0 mt-3">This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>

			<div class="col-lg-4 col-md-6 mt-4 pt-4">
				<div class="card border-0 p-4 text-center rounded features features-classic feature-primary">
					<i class="uil uil-circuit icon h1"></i>

					<div class="content">
						<Link to="/" class="title text-dark h5">No Rocket Science</Link>

						<p class="text-muted mb-0 mt-3">This prevents repetitive patterns from and facilitates the comparison of different typefaces.</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>