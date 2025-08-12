<script lang="ts">
	import "../app.css";

	let { children } = $props();
</script>

{@render children?.()}

<footer style="padding-top: 8px; padding-bottom: 4px; font-size: var(--sl-font-size-small);" class="pad ctext">
	© donut6150 2021-present.<br/>This website was made using Svelte and shoelace.style :)
</footer>
