<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">All releases</h1>
<div class="pad ctext">
    <Fluent.TextBlock>Webpage containing all the releases of donut's calculator</Fluent.TextBlock>
</div>
<div class="pad">
	<Fluent.Expander>Release 0.2 Public Beta
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first public release!<br>Changelog:
				<ul>
				<li>Fixed #1</li>
				<li>New icon</li>
				<li>New function: Square root</li>
				<li>Added redistributables in case of DLL errors on launch</li>
				Keep in mind that this is a public beta release, so you may encounter bugs. Have fun :)</ul></Fluent.TextBlock>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.2_public-beta/v0.2_public-beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2_public-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2_public-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
    <Fluent.Expander>[PRE-RELEASE] 0.1 Alpha
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first release of this CLI calculator! Have fun :)</Fluent.TextBlock><br>
			<Fluent.TextBlock>Known bugs:<ul><li>Typing "exit" in the "enter two numbers" area results in a loop</li></ul></Fluent.TextBlock>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.1-alpha/calc.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.1-alpha.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.1-alpha.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
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