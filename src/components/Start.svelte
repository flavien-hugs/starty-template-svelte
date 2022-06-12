<script>
    import { Link } from 'svelte-routing';

    let app1 = 'assets/img/app/1.png'
    let app2 = 'assets/img/app/2.png'
    let app3 = 'assets/img/app/3.png'
    let src = 'assets/img/app/hand-with-mobile.png'
</script>

<section class="section overflow-hidden pb-0" id="services">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-4 col-md-6">
                <div class="card p-4 rounded features features-classic feature-primary">
                    <div class="fea-icon rounded bg-light shadow icon">
                        <i class="uil uil-airplay mb-0 text-primary"></i>
                    </div>
                    <div class="content mt-4">
                        <Link to="/" class="title h5 text-dark">Fast Performance</Link>

                        <p class="text-muted mt-3">It is said that song composers of the past used dummy texts as lyrics when writing to sing with the melody.</p>
                    </div>

                    <Link to="/">
                        <span class="text-dark">
                            Read More
                            <i class="uil uil-arrow-right"></i>
                        </span>
                    </Link>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mt-4 pt-2 mt-sm-0 pt-sm-0">
                <div class="card p-4 rounded features features-classic feature-primary">
                    <div class="fea-icon rounded bg-light shadow icon">
                        <i class="uil uil-atom mb-0 text-primary"></i>
                    </div>

                    <div class="content mt-4">
                        <Link to="page-single-service.html" class="title h5 text-dark">Prototyping</Link>

                        <p class="text-muted mt-3">It is said that song composers of the past used dummy texts as lyrics when writing to sing with the melody.</p>
                    </div>

                    <Link to="page-single-service.html">
                        <span class="text-dark">
                            Read More
                            <i class="uil uil-arrow-right"></i>
                        </span>
                    </Link>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mt-4 pt-2 mt-lg-0 pt-lg-0">
                <div class="card p-4 rounded features features-classic feature-primary">
                    <div class="fea-icon rounded bg-light shadow icon">
                        <i class="uil uil-users-alt mb-0 text-primary"></i>
                    </div>

                    <div class="content mt-4">
                        <Link to="#" class="title h5 text-dark">
                            Vector Editing
                        </Link>

                        <p class="text-muted mt-3">It is said that song composers of the past used dummy texts as lyrics when writing to sing with the melody.</p>
                    </div>

                    <Link to="#">
                        <span class="text-dark">
                            Read More <i class="uil uil-arrow-right"></i>
                        </span>
                    </Link>
                </div>
            </div>
        </div>
    </div>

    <div class="container mt-100 mt-60">
        <div class="row align-items-center">
            <div class="col-lg-5 col-md-6 order-md-1 order-2 mt-4 mt-am-0 pt-2 pt-sm-0">
                <div class="app-feature-shape position-relative">
                    <div class="tiny-single-item">
                        <div class="tiny-slide">
                            <img src={app1} class="img-fluid" alt="app-1">
                        </div>
                        <div class="tiny-slide">
                            <img src={app2} class="img-fluid" alt="app-2">
                        </div>
                        <div class="tiny-slide">
                            <img src={app3} class="img-fluid" alt="app-3">
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-lg-7 col-md-6 order-md-2 order-1">
                <div class="ms-lg-5">
                    <div class="section-title">
                        <h6 class="text-primary">Analytics</h6>

                        <h4 class="title mb-4">Organize your work <br> anywhere</h4>
                        <p class="text-muted para-desc mb-0">Explore and learn more about everything from machine learning and global payments to  scaling your team.</p>

                        <ul class="list-unstyled text-muted mt-3">
                            <li class="mb-0">
                                <span class="text-primary h5 me-2">
                                    <i class="uil uil-check-circle align-middle"></i>
                                </span>
                                Digital Marketing Solutions for Tomorrow
                            </li>

                            <li class="mb-0">
                                <span class="text-primary h5 me-2">
                                    <i class="uil uil-check-circle align-middle"></i>
                                </span>
                                Our Talented & Experienced Marketing Agency
                            </li>

                            <li class="mb-0">
                                <span class="text-primary h5 me-2">
                                    <i class="uil uil-check-circle align-middle"></i>
                                </span>Create your own skin to match your brand
                            </li>
                        </ul>

                        <div class="mt-4">
                            <Link to="" class="btn btn-soft-primary">
                                Try for free
                                <i data-feather="arrow-right" class="fea icon-sm"></i>
                            </Link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container mt-100 mt-60">
        <div class="row align-items-lg-center align-items-end">
            <div class="col-md-6">
                <div class="section-title mb-4 pb-2">
                    <h4 class="title mb-4">Designed & Built by the <br> latest code integration</h4>

                    <p class="text-muted para-desc mb-0">Explore and learn more about everything from machine learning and global payments to  scaling your team.</p>

                    <ul class="list-unstyled mb-0">
                        <li class="d-flex mt-4">
                            <i class="uil uil-check-circle h4 text-primary"></i>

                            <div class="flex-1 ms-3">
                                <h6 class="mb-0">Buy, sell, and trade on the go</h6>
                                <p class="text-muted mt-2 mb-0">Manage your holdings from your mobile device</p>
                            </div>
                        </li>

                        <li class="d-flex mt-4">
                            <i class="uil uil-check-circle h4 text-primary"></i>

                            <div class="flex-1 ms-3">
                                <h6 class="mb-0">Take control of your wealth</h6>
                                <p class="text-muted mt-2 mb-0">Rest assured you (and only you) have access to your funds</p>
                            </div>
                        </li>
                    </ul>

                    <div class="mt-4">
                        <Link to="" class="btn btn-primary">Download Now</Link>
                    </div>
                </div>
            </div>

            <div class="col-md-6">
                <div class="app-feature-shape position-relative">
                    <img {src} class="img-fluid" alt="hand">
                </div>
            </div>
        </div>
    </div>
</section>
