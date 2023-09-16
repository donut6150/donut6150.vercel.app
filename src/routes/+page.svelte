<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = false;
</script>
<h1 class="ctext">donut2008</h1>
<div class="pad ctext">
	<Fluent.TextBlock>Welcome to donut2008's homepage!</Fluent.TextBlock>
</div>
<div class="pad card">
	<h2>About me</h2>
	<Fluent.TextBlock>(Pseudo?) developer learning C#, C++, Java, HTML, and CSS. Always open to friendly DMs.</Fluent.TextBlock>
		<p></p>
		<Fluent.TextBlock>You can find me here:
			<ul>
				<li>Discord - donut2008 / donut2008_ (alt)</li>
				<li>Telegram - @donut2008</li>
				<li>GitHub - donut2008</li>
			</ul>
		</Fluent.TextBlock>
</div>
<div class="pad">
	<Fluent.Expander>About me
	<svelte:fragment slot="content">
		<Fluent.TextBlock>(Pseudo?) developer learning C#, C++, Java, HTML, and CSS. Always open to friendly DMs.</Fluent.TextBlock>
		<p></p>
		<Fluent.TextBlock>You can find me here:
			<ul>
				<li>Discord - donut2008 / donut2008_ (alt)</li>
				<li>Telegram - @donut2008</li>
				<li>GitHub - donut2008</li>
			</ul>
		</Fluent.TextBlock>
	</svelte:fragment>
</Fluent.Expander>
	<Fluent.Expander>GitHub projects (active/dormant)
		<svelte:fragment slot="content">
			<ul>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/Calculator" target="_blank" rel="noopener noreferrer">Calculator</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/NeonX" target="_blank" rel="noopener noreferrer">NeonX</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/UWPDrawingCanvas" target="_blank" rel="noopener noreferrer">Drawing Canvas UWP</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/DonutOS" target="_blank" rel="noopener noreferrer">DonutOS</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/WinTranslate" target="_blank" rel="noopener noreferrer">WinTranslate</Fluent.Button></li>
			</ul>
		</svelte:fragment>
	</Fluent.Expander>
	<Fluent.Expander>Credits
		<svelte:fragment slot="content">
			<ul>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/Tropix126" target="_blank" rel="noopener noreferrer">Tropix126</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/TheOnlyTails" target="_blank" rel="noopener noreferrer">TheOnlyTails</Fluent.Button></li>
			</ul>
			<p></p>
			Credits to them for porting Microsoft's Fluent UI to Svelte!
		</svelte:fragment>
	</Fluent.Expander>
</div>
<p></p>

<style>
	:root {
		font-family: var(--fds-font-family-display);
		
	}
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media(prefers-color-scheme: light){
		:root{
			font-size: 16px;
			text-align: left;
			color: black;
			background: var(--fds-acrylic-background-base);
		}
	}
	@media(prefers-color-scheme: dark){
		:root{
			font-size: 16px;
			text-align: left;
			color: white;
			background: var(--fds-acrylic-background-base);
		}
	}
	.pad {
		padding: 16px 8px;
	}
	.ctext {
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
	.card {
		border-radius: 8px;
		background: var(--fds-acrylic-background-default);
		box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
	}
</style>