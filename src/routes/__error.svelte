<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
	import * as Fluent from "fluent-svelte";
    </script>

<Header />

<main>
	<slot/>
</main>

<footer>
	<div class="pad">
        <div class="textalign">
            <img src="./error.gif" alt="error">
        </div>
        <h1 class="ctext">Whoops, there seems to be an error...</h1>
    </div>
    <div class="pad">
        <Fluent.TextBlock>The requested page either does not exist, or didn't load correctly.</Fluent.TextBlock>
    </div>
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
	.textalign {
		text-align: center;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
	h1 {
		font-size: 40px;
	}
    .ctext {
		text-align: center;
	}
</style>
