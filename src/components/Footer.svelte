<script>
    import { Link } from 'svelte-routing'
    import ArrowUp from "svelte-material-icons/ArrowUp.svelte"
    
    const topFunction = () => {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
    }

    let llight = 'assets/img/llight.png'
</script>

<footer class="footer bg-footer">
    <div class="py-5 footer-border-bottom">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-8">
                    <div class="section-title">
                        <div class="d-flex">
                            <i class="uil uil-envelope-star display-4 text-white title-dark"></i>
                            <div class="flex-1 ms-md-4 ms-3">
                                <h4 class="fw-bold text-light title-dark mb-1">Subscribe to our newsletters</h4>
                                <p class="text-white-50 mb-0">Sign up and receive the latest tips via email.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 mt-4 mt-sm-0">
                    <div class="text-md-end ms-5 ms-sm-0">
                        <Link to="/" class="btn btn-primary">Subscribe Now</Link>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="footer-py-30 footer-bar bg-footer">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-sm-4">
                    <div class="text-sm-start text-center">
                        <Link to="/">
                            <img src={llight} height="26" alt="logo">
                        </Link>
                    </div>
                </div>

                <div class="col-sm-8 mt-4 mt-sm-0">
                    <div class="text-sm-end text-center">
                        <p class="mb-0 text-muted">
                            &copy; Flavien HUGS
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>

<span id="back-to-top" class="back-to-top rounded-pill">
    <ArrowUp/>
</span>
