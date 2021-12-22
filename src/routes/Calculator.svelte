<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">Calculator</h1>
<div class="pad ctext">
    <Fluent.TextBlock>Calculator written in C# with WinUI 2.7 controls</Fluent.TextBlock>
</div>
<div class="pad ctext">
    <Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v4.0.59/4.0.59-stable.zip">Download latest build</Fluent.Button>
    <Fluent.Button href="https://donut2008.github.io/Calculator/releases" target="_blank" rel="noopener noreferrer">View all releases</Fluent.Button>
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
<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media(prefers-color-scheme: light){
		:root{
			font-size: 16px;
			text-align: left;
			color: black;
			
		}
		::-webkit-scrollbar {
		  width: 8px;
		}
		::-webkit-scrollbar-track {
		  background: transparent; 
		}
		::-webkit-scrollbar-thumb {
		  background: #555;
		  border-radius: 10px;
		  padding: 2px;
		}
		::-webkit-scrollbar-thumb:hover {
		  background: #888;
		}
	}
	@media(prefers-color-scheme: dark){
		:root{
			font-size: 16px;
			text-align: left;
			color: white;
		}
		::-webkit-scrollbar {
		  width: 8px;
		}
		::-webkit-scrollbar-track {
		  background: transparent; 
		}
		::-webkit-scrollbar-thumb {
		  background: rgb(155, 155, 155);
		  border-radius: 10px;
		  padding: 2px;
		}
		::-webkit-scrollbar-thumb:hover {
		  background: rgb(129, 129, 129);
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
