<script>
	import { Router,Route} from "svelte-routing";
	import Navbar from "./components/navbar/Navbar.svelte";
	import About from "./views/About.svelte";
	import Contact from "./views/Contact.svelte";
	import Works from "./views/Works.svelte";
</script>

<main class="bg-gray-900 text-white relative z-0">
	<Router>
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
