<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>



<div class="m-2">

<nav>

	<Header />

	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>

</nav>

</div>