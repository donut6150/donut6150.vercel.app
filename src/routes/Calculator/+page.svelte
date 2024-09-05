<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">Calculator</h1>
<div class="pad ctext">
    <Fluent.TextBlock>Calculator written in C#.</Fluent.TextBlock>
</div>
<div class="pad ctext">
    <Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v5.0.60/5.0.60_stable.zip">Download latest build</Fluent.Button>
    <Fluent.Button href="Calculator/releases" target="_blank" rel="noopener noreferrer">View all releases</Fluent.Button>
</div>
<div class="pad">
	<Fluent.Expander>Screenshots (light mode)
		<svelte:fragment slot="content">
			<table>
				<tr>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921792827149680760/unknown.png" alt="main page" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921792990178050048/unknown.png" alt="temperature" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921793182868586586/unknown.png" alt="settings" style="width:100%;height:100%;"></td>
				</tr>
			</table>
		</svelte:fragment>
	</Fluent.Expander>
	<Fluent.Expander>Screenshots (dark mode)
		<svelte:fragment slot="content">
			<table>
				<tr>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921793771455250512/unknown.png" alt="main page" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921793651892436992/unknown.png" alt="temperature" style="width:100%;height:100%;"></td>
					<td><img src="https://cdn.discordapp.com/attachments/911987351784419408/921793549064888360/unknown.png" alt="settings" style="width:100%;height:100%;"></td>
				</tr>
			</table>
		</svelte:fragment>
	</Fluent.Expander>
</div>