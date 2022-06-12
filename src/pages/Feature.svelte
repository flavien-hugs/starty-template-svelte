<script>
	import { Link } from 'svelte-routing'

	export let router = {};

    router.path;
    router.route;
    router.params;

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

		<div class="position-middle-bottom">
			<nav aria-label="breadcrumb" class="d-block">
				<ul class="breadcrumb breadcrumb-muted mb-0 p-0">
					<li class="breadcrumb-item">
						<Link to="/">Starty</Link>
					</li>
				</ul>
			</nav>
		</div>
	</div>
</section>
