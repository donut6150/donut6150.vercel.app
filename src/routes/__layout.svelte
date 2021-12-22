<script lang="ts">
	import '../app.css';
	import * as Fluent from "fluent-svelte";
	let dialogOpen = false;
</script>

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
	}
	@media(prefers-color-scheme: dark){
		:root{
			font-size: 16px;
			text-align: left;
			color: white;
		}
		::-webkit-scrollbar {
		  width: 8px;
		}
		::-webkit-scrollbar-track {
		  background: transparent; 
		}
		::-webkit-scrollbar-thumb {
		  background: rgb(155, 155, 155);
		  border-radius: 10px;
		  padding: 2px;
		}
		::-webkit-scrollbar-thumb:hover {
		  background: rgb(129, 129, 129);
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
