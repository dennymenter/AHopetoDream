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

	
</nav>

</div>