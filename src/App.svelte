<script>
	import { Router } from 'svelte-routing'

	// Import Components
	import Hero from './components/Hero.svelte';
	import Header from './components/Header.svelte';
	import Partner from './components/Partner.svelte';
	import Start from './components/Start.svelte';
</script>

<Router>
	<Header/>

	<Hero/>
	<Partner/>
	<Start/>
</Router>
