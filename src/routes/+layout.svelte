<script>
	import "../app.css";
	import Nav from './Header.svelte';
	import Sidebar from './Sidebar.svelte';
	import './styles.css';
</script>

<div class="app">
	<Nav />
	<Sidebar />

	<main class="p-4 sm:ml-64">
		<div class="p-4 dark:border-gray-700 mt-14">
			<slot />
		</div>
	</main>
</div>

<style lang="postcss">
</style>
