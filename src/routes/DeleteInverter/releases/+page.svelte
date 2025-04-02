<script>
	import { TextBlock, Expander, Button } from "fluent-svelte"; 
	import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">DeleteInverter: releases</h1>
<div class="pad ctext">
	<TextBlock>All releases of DeleteInverter</TextBlock>
</div>
<div class="pad">
	<Expander>
		<TextBlock variant="subtitle">1.1.0</TextBlock>
		<br><br>
		<TextBlock variant="caption">Released on: Feb 21, 2025</TextBlock>
		<svelte:fragment slot="content">
			<TextBlock>
                <ul>
                    <li>Fixed crash on attempting to delete files</li>
                    <li>Added more info in help</li>
                </ul>
            </TextBlock>
			<div class="pad ctext">
				<Button variant="accent" href="https://github.com/donut2008/DeleteInverter/releases/download/1.1.0/DeleteInverter_1.1.0.0.zip">Download</Button>
				<Button href="https://github.com/donut2008/DeleteInverter/archive/refs/tags/1.1.0.zip">Source code (zip)</Button>
				<Button href="https://github.com/donut2008/DeleteInverter/archive/refs/tags/1.1.0.tar.gz">Source code (tar.gz)</Button>
			</div>
		</svelte:fragment>
	</Expander>
</div>
<div class="pad">
	<Expander>
		<TextBlock variant="subtitle">1.0.0</TextBlock>
        <br><br>
        <TextBlock variant="caption">Released on: Aug 26, 2024</TextBlock>
		<svelte:fragment slot="content">
			<TextBlock>Initial release!</TextBlock>
            <div class="pad ctext">
                <Button variant="accent" href="https://github.com/donut2008/DeleteInverter/releases/download/1.0.0/DeleteInverter_1.0.0.0_ARM.appx">Download (ARM)</Button>
                <Button variant="accent" href="https://github.com/donut2008/DeleteInverter/releases/download/1.0.0/DeleteInverter_1.0.0.0_x64.appx">Download (x64)</Button>
                <Button variant="accent" href="https://github.com/donut2008/DeleteInverter/releases/download/1.0.0/DeleteInverter_1.0.0.0_x86.appx">Download (x86)</Button>
                <Button href="https://github.com/donut2008/DeleteInverter/archive/refs/tags/1.0.0.zip">Source code (zip)</Button>
                <Button href="https://github.com/donut2008/DeleteInverter/archive/refs/tags/1.0.0.tar.gz">Source code (tar.gz)</Button>
            </div>
        </svelte:fragment>
    </Expander>
</div>