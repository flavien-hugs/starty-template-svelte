<script>
    // Plugins
    import { Link } from 'svelte-routing';

    // Import Images
    let bgapp = "assets/img/apps.jpg";
    let hero = "assets/img/app/hero.png";
</script>

<section class="bg-half-260 pb-lg-0 pb-md-4 d-table w-100" style="background: url({bgapp}) no-repeat center;" id="home">
    <div class="bg-overlay bg-gradient-primary opacity-9"></div>
    <div class="container">
        <div class="row position-relative" style="z-index: 1;">
            <div class="col-md-7 col-12 mt-lg-5">
                <div class="title-heading">
                    <h1 class="heading text-white title-dark mb-4">Essential Mobile App <br> for Workspaces</h1>
                    <p class="para-desc text-white-50">Explore and learn more about everything from machine learning and global payments to scaling your team.</p>
                    <div class="mt-4 pt-2">
                        <Link to="" class="btn btn-primary">
                            Start Free Trial
                        </Link>
                    </div>
                </div>
            </div>

            <div class="col-md-5 col-12 mt-4 pt-2 mt-sm-0 pt-sm-0">
                <div class="shape-before">
                    <div class="carousel-cell">
                        <img src={hero} class="img-fluid" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<div class="position-relative">
    <div class="shape overflow-hidden text-white">
        <svg viewBox="0 0 2880 250" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M720 125L2160 0H2880V250H0V125H720Z" fill="currentColor"></path>
        </svg>
    </div>
</div>
