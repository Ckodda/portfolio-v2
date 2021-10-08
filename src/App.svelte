<script>
	import { Router,Route} from "svelte-routing";
	import Navbar from "./components/navbar/Navbar.svelte";
	import About from "./views/About.svelte";
	import Contact from "./views/Contact.svelte";
	import Works from "./views/Works.svelte";
</script>

<main class="bg-gradient-to-r from-gray-800 to-gray-900 text-white relative z-0 overflow-hidden">

	<!--
	<div class="absolute z-0 w-2/4 h-full bg-gray-800">

	</div>
	-->
	
	<Router >
		<Navbar></Navbar>

		<Route path="/">
			<About></About>
		</Route>
		<Route path="/about">
			<About></About>
		</Route>
		<Route path="/works">
			<Works></Works>
		</Route>
		<Route path="/contact">
			<Contact></Contact>
		</Route>

	</Router>
	
</main>