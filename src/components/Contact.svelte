<script>
    import FormContact from '../layouts/FormContact.svelte';
</script>

<section class="section" id="contact">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="section-title mb-5 pb-2 text-center">
                    <h4 class="title mb-3">Get In Touch !</h4>
                    <p class="text-muted para-desc mx-auto mb-0">
                        Our design projects are fresh and simple and will benefit your business greatly. Learn more about our work!
                    </p>
                </div>
                <div class="custom-form">
                    <form method="post" name="myForm">

                        <FormContact/>

                        <div class="row">
                            <div class="col-12">
                                <div class="d-grid">
                                    <button type="submit" id="submit" name="send" class="btn btn-primary">
                                    Send Message</button>
                                </div>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>
