<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = false;
</script>

<svelte:head>
	<div class="head">
		donut2008
	</div>
</svelte:head>
<div class="pad">
	<Fluent.TextBlock>Welcome to donut2008's homepage!</Fluent.TextBlock>
</div>
<div class="pad">
<Fluent.Button variant="accent" href="https://github.com/donut2008" target="_blank" rel="noopener noreferrer">GitHub</Fluent.Button>
&nbsp;
<Fluent.Button variant="accent" href="https://t.me/donut2008" target="_blank" rel="noopener noreferrer">Telegram</Fluent.Button>
&nbsp;
<Fluent.Button variant="accent" on:click={()=>{dialogOpen=true}}>Discord</Fluent.Button>
<Fluent.ContentDialog bind:open={dialogOpen} title="Opening profiles through URLs aren't implemented into Discord for now.">
	<div style="display: flex; flex-direction: column; gap: 3px; margin: 0;">
		<Fluent.TextBlock>Send me a friend request on Discord (donut2008#7112) in order to DM me there.</Fluent.TextBlock>
	</div>
	<svelte:fragment slot="footer">
		<Fluent.Button variant="accent" on:click={() => { dialogOpen = false; }}>OK</Fluent.Button>
	</svelte:fragment>
</Fluent.ContentDialog>
</div>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");

	.head{
		font-size: 50px;
		text-align: center;
		font-weight: bold;
	}
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
		text-align: center;
	}
	.textalign {
		text-align: center;
	}
</style>