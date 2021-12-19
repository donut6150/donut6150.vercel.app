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
	<Fluent.Expander>[PRE-RELEASE] 0.5.1 build 021021-2031
		<svelte:fragment slot="content">
			<Fluent.TextBlock>This is the first major release, though it is quite buggy at the moment<br><br>Features:<ul>
				<li>Language changed from C++ to C#</li>
				<li>New interface</li>
				<li>Supports devices with Windows 10 build 15063 and above (Mobile as well!)</li></ul>
				Known bugs:
				<ul>
				<li>Square, square root, cube, and cube root crash the app</li>
				<li>Entering a digit, clicking Backspace and clicking "=" results in a crash</li>
				<li>Header background is white, temporary fix is clicking on any button</li></ul>These bugs are the reason why the CLI version is included in this release as well. Create a new issue if you find any bugs, along with a probable fix because I'm new to C#</Fluent.TextBlock><br>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
	<Fluent.Expander>Release 0.4 build 250921-1948 (September 25, 2021)
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Development was stopped temporarily because of exams, so there's nothing much except for the "power" function being fixed and a new build number pattern.</Fluent.TextBlock><br>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.4_build.250921-1948/v0.4_build.250921-1948.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.4_build.250921-1948.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.4_build.250921-1948.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
	<Fluent.Expander>Release 0.3 Beta (August 24, 2021)
		<svelte:fragment slot="content">
			<Fluent.TextBlock>New release!<br><br>Changelog:
				<ul>
					<li>Added an installer and uninstaller!</li>
					<li>32 bit support might have been dropped, Visual Studio is weird</li>
					<li>Changed Project Type from Debug to Release because of DLL errors</li>
					<li>Dropped "power" function support temporarily</li>
				</ul>
				Let me know whether this works on 32 bit systems or not by creating an issue.<br>
			</Fluent.TextBlock>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.3-beta/v0.3_beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.3-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.3-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
	<Fluent.Expander>Release 0.2.1 Public Beta (August 21, 2021)
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Minor release.<br><br>Changelog:
			<ul>
				<li>New functions: Cube root and power</li>
			Keep in mind this is still in beta, if you encounter any bugs don't hesitate to report them! :)</ul></Fluent.TextBlock>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.2.1_public-beta/v0.2.1_public-beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2.1_public-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2.1_public-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
	<Fluent.Expander>Release 0.2 Public Beta (August 21, 2021)
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first public release!<br><br>Changelog:
				<ul>
				<li>Fixed #1</li>
				<li>New icon</li>
				<li>New function: Square root</li>
				<li>Added redistributables in case of DLL errors on launch</li>
				</ul>
			Keep in mind that this is a public beta release, so you may encounter bugs. Have fun :)<br></Fluent.TextBlock>
			<div class="ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/Calculator/releases/download/v0.2_public-beta/v0.2_public-beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2_public-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/Calculator/archive/refs/tags/v0.2_public-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
    <Fluent.Expander>[PRE-RELEASE] 0.1 Alpha (August 20, 2021)
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first release of this CLI calculator! Have fun :)</Fluent.TextBlock><br><br>
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