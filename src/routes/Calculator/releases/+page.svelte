<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">Calculator: releases</h1>
<div class="pad ctext">
    <Fluent.TextBlock>All releases of Calculator</Fluent.TextBlock>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 5 build 60</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: December 24, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>After over a month of trial and error, the app finally has an operation history pane!<br>Check it out! It's in the main page, click the → symbol on the top left to open it.<br><br>I'll be in holiday mood until 3rd January 2022, happy holidays and Merry Christmas!</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v5.0.60/5.0.60_stable.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v5.0.60.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v5.0.60.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 4 build 59</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: November 23, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>(i swear this is the final build pattern LOL)
				<ul>
					<li>Reverted the font to Segoe UI</li>
					<li>Settings and Temperature pages no longer use a bold font for the page title</li>
					<li>Detailed build info is present in the Settings page</li>
				</ul>
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v4.0.59/4.0.59-stable.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v4.0.59.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v4.0.59.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 4.0 stable build 211111-1333</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: November 11, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Changelog:
				<ul>
					<li>Added a temperature converter!</li>
					<li>Font has been changed to Segoe UI Variable throughout the app</li>
				</ul>
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v4.0-stable_211111-1333/4.0.stable.build.211111-1333.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v4.0-stable_211111-1333.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v4.0-stable_211111-1333.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 3.0 stable build 211109-1951</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: November 9, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Features:
				<ul>
					<li>New icon (Windows Calculator Prototype 3, credits to Microsoft for making that)</li>
					<li>Themes! (Only light/dark/system default at the moment)</li>
				</ul>
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v3.0-stable_211109-1951/3.0.stable.build.211109-1951.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v3.0-stable_211109-1951.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v3.0-stable_211109-1951.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 2.0 stable build 211104-1312</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: November 6, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Fixed alignment of GitHub button in About page</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v2.0_211104-1312/2.0.stable.build.211104-1312.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v2.0_211104-1312.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v2.0_211104-1312.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 1.0 stable build 211102-1420</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: November 2, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Big jump :O<br><br>Features:
				<ul>
					<li>New functions! log, nPr, nCr, LN, sin, sin-1, cos, cos-1, tan, tan-1, factorial and 1/X</li>
					<li>Settings page has been changed to an "About" page (seriously what settings do you expect from a calculator)</li>
					<li>New build number pattern (final pattern, YYMMDD-HHmm)</li>
				</ul>
				Enjoy!
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v2.0_211104-1312/2.0.stable.build.211104-1312.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v2.0_211104-1312.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v2.0_211104-1312.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 0.6.5 stable build 171021-1652</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: October 17, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first proper release!<br><br>New features:
				<ul>
					<li>Working Settings page (still needs improvements, currently shows build info</li>
					<li>WinUI 2.7 controls</li>
					<li>Mica (only visible on Windows 11)!</li>
				</ul>
				Bug fixes:
				<ul>
					<li>Cube root, cube, square root, and square now work as expected</li>
					<li>Backspace no longer crashes the app</li>
					<li>Now has a responsive interface which responds to window resize events</li>
				</ul>
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/0.6.5-stable_171021-1652/0.6.5-stable_171021-1652.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/0.6.5-stable_171021-1652.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/0.6.5-stable_171021-1652.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">[PRE-RELEASE] 0.5.1 build 021021-2031</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: October 2, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>This is the first major release, though it is quite buggy at the moment<br><br>Features:
				<ul>
					<li>Language changed from C++ to C#</li>
					<li>New interface</li>
					<li>Supports devices with Windows 10 build 15063 and above (Mobile as well!)</li>
				</ul>
				Known bugs:
				<ul>
					<li>Square, square root, cube, and cube root crash the app</li>
					<li>Entering a digit, clicking Backspace and clicking "=" results in a crash</li>
					<li>Header background is white, temporary fix is clicking on any button</li>
				</ul>These bugs are the reason why the CLI version is included in this release as well. Create a new issue if you find any bugs, along with a probable fix because I'm new to C#</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.5.1-preview_021021-2031/CalculatorGUI_0.5.1.zip">Download (GUI)</Fluent.Button>
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.5.1-preview_021021-2031/v0.4_build.250921-1948.zip">Download (CLI)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.5.1-preview_021021-2031.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.5.1-preview_021021-2031.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 0.4 build 250921-1948</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: September 25, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Development was stopped temporarily because of exams, so there's nothing much except for the "power" function being fixed and a new build number pattern.</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.4_build.250921-1948/v0.4_build.250921-1948.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.4_build.250921-1948.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.4_build.250921-1948.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 0.3 Beta</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: August 24, 2021</Fluent.TextBlock>
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
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.3-beta/v0.3_beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.3-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.3-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 0.2.1 Public Beta</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: August 21, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Minor release.<br><br>Changelog:
			<ul>
				<li>New functions: Cube root and power</li>
			Keep in mind this is still in beta, if you encounter any bugs don't hesitate to report them! :)</ul></Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.2.1_public-beta/v0.2.1_public-beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.2.1_public-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.2.1_public-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
	<Fluent.Expander><Fluent.TextBlock variant="subtitle">Release 0.2 Public Beta</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: August 21, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first public release!<br><br>Changelog:
				<ul>
				<li>Fixed #1</li>
				<li>New icon</li>
				<li>New function: Square root</li>
				<li>Added redistributables in case of DLL errors on launch</li>
				</ul>
			Keep in mind that this is a public beta release, so you may encounter bugs. Have fun :)<br></Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.2_public-beta/v0.2_public-beta.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.2_public-beta.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.2_public-beta.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div>
    <Fluent.Expander><Fluent.TextBlock variant="subtitle">[PRE-RELEASE] 0.1 Alpha</Fluent.TextBlock><br><br><Fluent.TextBlock variant="caption">Released on: August 20, 2021</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>The first release of this CLI calculator! Have fun :)</Fluent.TextBlock><br><br>
			<Fluent.TextBlock>Known bugs:<ul><li>Typing "exit" in the "enter two numbers" area results in a loop</li></ul></Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut6150/Calculator/releases/download/v0.1-alpha/calc.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.1-alpha.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut6150/Calculator/archive/refs/tags/v0.1-alpha.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>