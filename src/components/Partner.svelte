<script>
    import Image from '../layouts/Image.svelte';

    let one = 'assets/img/client/logo-1.svg';
    let two = 'assets/img/client/logo-2.svg';
    let three = 'assets/img/client/logo-3.svg';
    let four = 'assets/img/client/logo-4.svg';
    let five = 'assets/img/client/logo-5.svg';
    let six = 'assets/img/client/logo-6.svg';
</script>


<section class="pt-4">
    <div class="container">
        <div class="row justify-content-center">
            <Image src={one}/>
            <Image src={two}/>
            <Image src={three}/>
            <Image src={four}/>
            <Image src={five}/>
            <Image src={six}/>
        </div>
    </div>
</section>
