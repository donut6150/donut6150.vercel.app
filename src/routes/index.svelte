<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = false;
	let dialogOpen1 = false;
</script>
<h1 class="ctext">donut2008</h1>
<div class="pad ctext">
	<Fluent.TextBlock>Welcome to donut2008's homepage!</Fluent.TextBlock>
</div>
<div class="pad ctext">
<Fluent.Button variant="accent" href="https://github.com/donut2008" target="_blank" rel="noopener noreferrer">GitHub</Fluent.Button>
&nbsp;
<Fluent.Button variant="accent" href="https://t.me/donut2008" target="_blank" rel="noopener noreferrer">Telegram</Fluent.Button>
&nbsp;
<Fluent.Button variant="accent" on:click={()=>{dialogOpen=true}}>Discord</Fluent.Button>
<Fluent.ContentDialog bind:open={dialogOpen} style="text-align: left;" title="Opening profiles through URLs aren't implemented into Discord for now.">
	<div style="display: flex; flex-direction: column; gap: 3px; margin: 0;">
		<Fluent.TextBlock style="text-align: left;">Send me a friend request on Discord (donut2008#7112) in order to DM me there.</Fluent.TextBlock>
	</div>
	<svelte:fragment slot="footer">
		<Fluent.Button variant="accent" on:click={() => { dialogOpen = false; }}>OK</Fluent.Button>
	</svelte:fragment>
</Fluent.ContentDialog>
</div>
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
	<Fluent.Expander>GitHub projects
		<svelte:fragment slot="content">
			<ul>
				<li><Fluent.Button variant="hyperlink" href="https://donut2008.github.io/Calculator" target="_blank" rel="noopener noreferrer">Calculator</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/donut2008/NeonX" target="_blank" rel="noopener noreferrer">NeonX (forked from Alur2020/NeonX)</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/donut2008/UWPDrawingCanvas" target="_blank" rel="noopener noreferrer">Drawing Canvas UWP</Fluent.Button></li>
			</ul>
		</svelte:fragment>
	</Fluent.Expander>
	<Fluent.Expander>Devices I have
		<svelte:fragment slot="content">
			<ul>
				<li>HP 15s fr2006tu, specifications:<br>11th gen Intel core i3 1115G4<br>8 GB DDR4 RAM<br>15.6 inch 1080p IPS display<br>512 GB NVMe SSD</li>
				<li>Samsung Galaxy M02 black (32/2 variant) running Android 11, rooted</li>
				<li>Microsoft Lumia 540 running Windows 10 Mobile 1607</li>
				<li>Logitech M185 wireless mouse</li>
				<li>LG 32" 1080p TV from 2015</li>
				<li>Sony MDR ZX110 headphones</li>
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
			Amazing thanks for porting Microsoft's Fluent UI to Svelte!
		</svelte:fragment>
	</Fluent.Expander>
</div>
<p></p>

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
	.pad {
		padding: 8px;
	}
	.ctext {
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
</style>