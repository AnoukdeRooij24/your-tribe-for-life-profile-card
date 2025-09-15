<script>
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<!-- Hier kan de header + nav komen -->

<main>
	{@render children?.()}
</main>

<!-- Hier kan de footer komen -->