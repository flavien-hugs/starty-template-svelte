<script>
	import { Router } from 'svelte-routing'

	// component.svelte
	import Hero from './components/Hero.svelte';
	import Start from './components/Start.svelte';
	import Footer from './components/Footer.svelte';
	import Header from './components/Header.svelte';
	import Partner from './components/Partner.svelte';
	import Contact from './components/Contact.svelte';
</script>

<Router>
	<Header/>

	<Hero/>
	<Partner/>
	<Start/>
	<Contact/>
	<Footer/>
</Router>
