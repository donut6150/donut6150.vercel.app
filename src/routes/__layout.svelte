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
	<div class="pad">
		<Fluent.Expander>About me
		<svelte:fragment slot="content">
			<Fluent.TextBlock>13 y.o (pseudo?) developer learning C#, C++, JS, HTML, and CSS. Always open to friendly DMs.</Fluent.TextBlock>
			<p></p>
			<Fluent.TextBlock>You can find me here:
				<ul>
					<li>Discord - donut2008#7112</li>
					<li>Telegram - @donut2008</li>
					<li>GitHub - donut2008</li>
				</ul>
			</Fluent.TextBlock>
		</svelte:fragment>
	</Fluent.Expander>
	</div>
	<div class="pad">
		<Fluent.Expander>GitHub projects
			<svelte:fragment slot="content">
				<ul>
					<li><Fluent.Button variant="hyperlink" href="https://github.com/donut2008/Calculator" target="_blank" rel="noopener noreferrer">Calculator</Fluent.Button></li>
					<li><Fluent.Button variant="hyperlink" href="https://github.com/donut2008/NeonX" target="_blank" rel="noopener noreferrer">NeonX</Fluent.Button></li>
				</ul>
			</svelte:fragment>
		</Fluent.Expander>
		</div>
	<p>Still work in progress, expect more stuff to come soon!</p>
</footer>

<style>
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
