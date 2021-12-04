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
			<Fluent.TextBlock>(Pseudo?) developer learning C#, C++, JS, HTML, and CSS. Always open to friendly DMs.</Fluent.TextBlock>
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
	<div class="pad">
		<Fluent.Expander>Devices I have
			<svelte:fragment slot="content">
				<ul>
					<li>HP 15s fr2006tu (laptop) running Windows 11 insider build 22509. Specifications:<br>11th gen Intel core i3 1115G4<br>8 GB DDR4 RAM<br>15.6 inch 1080p IPS display<br>512 GB NVMe SSD</li>
					<li>Samsung Galaxy M02 black (32/2 variant) running Android 11, rooted</li>
					<li>Microsoft Lumia 540 running Windows 10 Mobile 1709</li>
					<li>Logitech M185 wireless mouse</li>
					<li>LG 32" 1080p TV from 2015</li>
				</ul>
			</svelte:fragment>
		</Fluent.Expander>
	</div>
	<p></p>
	<div class="textalign">Huge thanks to <Fluent.Button variant="hyperlink" href="https://github.com/Tropix126/">Tropix126</Fluent.Button> and <Fluent.Button variant="hyperlink" href="https://github.com/TheOnlyTails">TheOnlyTails</Fluent.Button>. This website was possible thanks to their amazing work of porting Microsoft's Fluent UI to Svelte.<br>Check out the <Fluent.Button variant="hyperlink" href="https://github.com/Tropix126/fluent-svelte">repo</Fluent.Button>!</div>
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
	.textalign {
		text-align: center;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
</style>
