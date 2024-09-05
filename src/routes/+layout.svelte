<script lang="ts">
	import "../app.css";
	import { TextBlock } from "fluent-svelte";
</script>

<main>
	<slot />
</main>

<footer>
	<TextBlock>© donut2008 2021-present.</TextBlock>
</footer>

<style>
	@import url("../app.css");
	:root {
		font-family: var(--fds-font-family-display);
		font-size: 16px;
		text-align: left;
	}
	@media (prefers-color-scheme: light) {
		:root {
			color: black;
			background-color: var(--fds-solid-background-base);
		}
	}
	@media (prefers-color-scheme: dark) {
		:root {
			color: white;
			background-color: var(--fds-solid-background-base);
		}
	}
	::-webkit-scrollbar {
		width: 8px;
	}
	::-webkit-scrollbar-track {
		background: transparent;
	}
	::-webkit-scrollbar-thumb {
		background: #555;
		border-radius: 10px;
		padding: 2px;
	}
	::-webkit-scrollbar-thumb:hover {
		background: #888;
	}
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: stretch;
		align-items: center;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
</style>
