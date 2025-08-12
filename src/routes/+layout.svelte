<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';
	import "../app.css";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children?.()}

<footer style="padding-top: 8px; padding-bottom: 4px; font-size: var(--sl-font-size-small);" class="pad ctext">
	© donut6150 2021-present.<br/>This website was made using Svelte and shoelace.style :)
</footer>
