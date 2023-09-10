<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">WinTranslate</h1>
<div class="pad ctext">
	<Fluent.TextBlock>A WIP native Google Translate client written in C# and WinUI 3 for Windows 10 1809 and above.</Fluent.TextBlock>
</div>
<div class="pad ctext">
	<Fluent.TextBlock>More info coming soon!</Fluent.TextBlock>
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