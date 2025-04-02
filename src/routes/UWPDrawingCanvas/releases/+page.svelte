<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">Drawing Canvas: releases</h1>
<div class="pad ctext">
	<Fluent.TextBlock>All releases of Drawing Canvas</Fluent.TextBlock>
</div>
<div class="pad">
	<Fluent.Expander>
		<Fluent.TextBlock variant="subtitle">v2.5.100</Fluent.TextBlock>
		<br><br>
		<Fluent.TextBlock variant="caption">Released on: May 12, 2022</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>No updates for a long time, but I'm finally back!<br><br>Changelog:
				<ul>
					<li>Revamped UI</li>
					<li>New Settings page</li>
					<li>Added calligraphic pen</li>
					<li>Mica! (not in titlebar because the titlebar became un-draggable for some reason)</li>
				</ul>
				Known bugs:
				<ul>
					<li>Saving with a custom size does not work, the file will always be saved with the dimensions of the app window (currently being worked on)</li>
				</ul>
			Enjoy! :D
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/UWPDrawingCanvas/releases/download/v2.5/2.5.100.0_x86_x64.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/UWPDrawingCanvas/archive/refs/tags/v2.5.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/UWPDrawingCanvas/archive/refs/tags/v2.5.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>
<div class="pad">
	<Fluent.Expander>
		<Fluent.TextBlock variant="subtitle">Pre-release 1.0 build 64</Fluent.TextBlock>
		<svelte:fragment slot="content">
			<Fluent.TextBlock>Initial release! (rather, pre-release)<br><br>Known issues:
				<ul>
					<li>There is no color picker</li>
					<li>Ink settings don't get saved on closing the app</li>
				</ul>
			</Fluent.TextBlock>
			<div class="pad ctext">
				<Fluent.Button variant="accent" href="https://github.com/donut2008/UWPDrawingCanvas/releases/download/v1.0p/UWPDrawingCanvas_1.0p_64.zip">Download</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/UWPDrawingCanvas/archive/refs/tags/v1.0p.zip">Source code (zip)</Fluent.Button>
				<Fluent.Button href="https://github.com/donut2008/UWPDrawingCanvas/archive/refs/tags/v1.0p.tar.gz">Source code (tar.gz)</Fluent.Button>
			</div>
		</svelte:fragment>
	</Fluent.Expander>
</div>