<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
	import * as Fluent from "fluent-svelte";
	let dialogOpen = false;
</script>

<Header />

<main>
	<slot/>
</main>

<footer>
	
</footer>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media(prefers-color-scheme: light){
		:root{
			font-size: 16px;
			text-align: left;
			color: black;
		}
	}
	@media(prefers-color-scheme: dark){
		:root{
			font-size: 16px;
			text-align: left;
			color: white;
		}
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
		align-items: stretch;
		padding: 40px;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
</style>
