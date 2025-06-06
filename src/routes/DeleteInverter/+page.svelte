<script>
    import { TextBlock, Button, Expander } from "fluent-svelte";
    import "fluent-svelte/theme.css";
</script>
<h1 class="ctext">DeleteInverter</h1>
<div class="pad ctext">
    <TextBlock>An app which deletes files except the ones you manually select. Exclusions will not be deleted.</TextBlock>
</div>
<div class="pad ctext">
    <Button variant="accent" href="https://github.com/donut6150/DeleteInverter/releases/download/1.1.0/DeleteInverter_1.1.0.0.zip">Download latest build</Button>
    <Button href="DeleteInverter/releases" target="blank" rel="noopener noreferrer">View all releases</Button>
</div>
<div class="pad">
    <Expander>Screenshots (light mode)
        <svelte:fragment slot="content">
            <table>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
            </table>
        </svelte:fragment>
    </Expander>
    <Expander>Screenshots (dark mode)
        <svelte:fragment slot="content">
            <table>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
            </table>
        </svelte:fragment>
    </Expander>
</div>