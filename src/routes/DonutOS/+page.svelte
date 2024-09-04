<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">DonutOS</h1>
<div class="pad ctext">
	<Fluent.TextBlock>A (very) WIP operating system made in C# using <a href="https://github.com/CosmosOS/Cosmos">Cosmos</a>.</Fluent.TextBlock>
</div>
<div class="pad ctext">
	<Fluent.TextBlock>Current status: literally broken</Fluent.TextBlock>
</div>
<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media(prefers-color-scheme: light)
	{
		:root
		{
			font-size: 16px;
			text-align: left;
			color: black;
		}
	}
	@media(prefers-color-scheme: dark)
	{
		:root
		{
			font-size: 16px;
			text-align: left;
			color: white;
		}
	}
	.pad
	{
		padding: 8px;
	}
	.ctext
	{
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
</style>