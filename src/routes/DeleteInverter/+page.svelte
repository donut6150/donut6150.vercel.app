<script>
    import { TextBlock } from "fluent-svelte";
    import "fluent-svelte/theme.css";
</script>

<h1 class="ctext">DeleteInverter</h1>
<div class="pad ctext">
    <TextBlock>something something abcd</TextBlock>
</div>
<div class="pad ctext">
    <TextBlock>status</TextBlock>
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
