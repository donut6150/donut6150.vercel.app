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
                    <td><Fluent.TextBlock>yeah you have to wait until the UI revamp</Fluent.TextBlock></td>
                </tr>
            </table>
        </svelte:fragment>
    </Fluent.Expander>
    <Fluent.Expander>Screenshots (dark mode)
        <svelte:fragment slot="content">
            <table>
                <tr>
                    <td><Fluent.TextBlock>open the light mode screenshots expander</Fluent.TextBlock></td>
                </tr>
            </table>
        </svelte:fragment>
    </Fluent.Expander>
</div>