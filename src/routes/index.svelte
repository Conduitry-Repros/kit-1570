<script>
	import { onMount } from 'svelte';

	if (false) {
		// UNCOMMENT THE FOLLOWING LINE TO TRIGGER THE BUG
		// import('@sentry/node');
	}

	onMount(async () => {
		console.log(await import('decoders'));
	})
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
