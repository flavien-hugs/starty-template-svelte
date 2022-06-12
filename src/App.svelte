<script>
	// plugins.svelte
	import { Router, Route } from 'svelte-routing'

	// pages.svelte
	import Home from './pages/Home.svelte';
	import Contact from './pages/Contact.svelte';
	import Feature from './pages/Feature.svelte';

	// components.svelte
	import Footer from './components/Footer.svelte';
	import Header from './components/Header.svelte';
</script>

<Router>
	<Header/>
	<Route path="/" component={Home}/>
	<Route path="/page/feature/" component={Feature}/>
	<Route path="/page/contact/" component={Contact}/>
	<Footer/>
</Router>
