<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = false;
</script>

<h1 class="ctext">donut2008</h1>
<div class="pad ctext">
	<Fluent.TextBlock>Welcome to donut2008's homepage!</Fluent.TextBlock>
</div>
<div class="card">
	<h2 class="pad bgs">About me</h2>
	<div class="pad">
		<Fluent.TextBlock>
			Some guy learning C#, C++, Java, HTML, and CSS. Always open to
			friendly DMs.
		</Fluent.TextBlock>
		<p />
		<Fluent.TextBlock>
			You can find me here:
			<ul>
				<li>Discord - donut2008 / donut2008_ (alt)</li>
				<li>Telegram - @donut2008</li>
				<li>GitHub - donut2008</li>
			</ul>
		</Fluent.TextBlock>
	</div>
</div>
<div class="card">
	<h2 class="pad bgs">GitHub projects (active/dormant)</h2>
	<div class="pad">
		<Fluent.TextBlock>
			<ul>
				<li>
					<Fluent.Button
						variant="hyperlink"
						href="https://donut2008.github.io/Calculator"
						target="_blank"
						rel="noopener noreferrer">Calculator</Fluent.Button
					>
				</li>
				<li>
					<Fluent.Button
						variant="hyperlink"
						href="https://donut2008.github.io/NeonX"
						target="_blank"
						rel="noopener noreferrer">NeonX</Fluent.Button
					>
				</li>
				<li>
					<Fluent.Button
						variant="hyperlink"
						href="https://donut2008.github.io/UWPDrawingCanvas"
						target="_blank"
						rel="noopener noreferrer"
						>Drawing Canvas UWP</Fluent.Button
					>
				</li>
				<li>
					<Fluent.Button
						variant="hyperlink"
						href="https://donut2008.github.io/DonutOS"
						target="_blank"
						rel="noopener noreferrer">DonutOS</Fluent.Button
					>
				</li>
				<li>
					<Fluent.Button
						variant="hyperlink"
						href="https://donut2008.github.io/WinTranslate"
						target="_blank"
						rel="noopener noreferrer">WinTranslate</Fluent.Button
					>
				</li>
			</ul>
		</Fluent.TextBlock>
	</div>
</div>
<footer class="fb">
	<Fluent.TextBlock variant="caption"
		>© donut2008 2023. All rights reserved.</Fluent.TextBlock
	>
	<a href="https://telegram.me/donut2008" target="_blank">
		<img src="/img/telegram.svg" alt="Telegram" />
	</a>
	<!-- github -->
	<!-- discord -->
</footer>

<style>
	:root {
		font-family: var(--fds-font-family-display);
	}
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media (prefers-color-scheme: light) {
		:root {
			font-size: 16px;
			text-align: left;
			color: black;
			background: var(--fds-acrylic-background-base);
		}
	}
	@media (prefers-color-scheme: dark) {
		:root {
			font-size: 16px;
			text-align: left;
			color: white;
			background: var(--fds-acrylic-background-base);
		}
	}
	.fb {
		text-align: center;
		background: var(--fds-solid-background-secondary);
		bottom: 0;
		left: 0;
		width: 100%;
		position: fixed;
		padding: 4px;
	}
	.pad {
		padding: 16px;
	}
	.ctext {
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
	.card {
		border-radius: 8px;
		background: var(--fds-card-background-default);
		box-shadow: var(--fds-card-shadow);
		border: var(--fds-control-border-default);
	}
	.bgs {
		background: var(--fds-card-background-secondary);
		border-radius: 8px 8px 0 0;
	}
</style>
