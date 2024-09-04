<script>
    import * as Fluent from "fluent-svelte";
    import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">Drawing Canvas</h1>
<div class="pad ctext">
    <Fluent.TextBlock>A UWP drawing canvas.</Fluent.TextBlock>
</div>
<div class="pad ctext">
    <Fluent.Button variant="accent" href="https://github.com/donut2008/UWPDrawingCanvas/releases/download/v2.5/2.5.100.0_x86_x64.zip">Download latest build</Fluent.Button>
    <Fluent.Button href="https://donut2008.github.io/UWPDrawingCanvas/releases" target="_blank" rel="noopener noreferrer">View all releases</Fluent.Button>
</div>
<div class="pad">
    <Fluent.Expander>Screenshots (light mode)
        <svelte:fragment slot="content">
            <table>
                <tr>
                    <td><img src="https://cdn.discordapp.com/attachments/911987351784419408/1018931178524393663/unknown.png" alt="main page light" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/1018931202142502912/unknown.png" alt="settings light" style="width:100%;height:100%;"></td>
                </tr>
            </table>
        </svelte:fragment>
    </Fluent.Expander>
    <Fluent.Expander>Screenshots (dark mode)
        <svelte:fragment slot="content">
            <table>
                <tr>
                    <td><img src="https://cdn.discordapp.com/attachments/911987351784419408/1018930938283036732/unknown.png" alt="main page dark" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/1018930996776812634/unknown.png" alt="settings dark" style="width:100%;height:100%;"></td>
                </tr>
            </table>
        </svelte:fragment>
    </Fluent.Expander>
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