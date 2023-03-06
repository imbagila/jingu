<script>
	import "../app.css";
	import Nav from './Nav.svelte';
	import Sidebar from './Sidebar.svelte';
	import './styles.css';
</script>

<div class="app">
	<Nav />
	<Sidebar />

	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>

<style lang="postcss">
</style>
