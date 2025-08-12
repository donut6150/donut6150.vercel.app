<script lang="ts">
    import '../app.css';
</script>

<main>
    <slot>
        <div class="pad">
            <div class="textalign">
                <img src="https://raw.githubusercontent.com/donut6150/donut6150.vercel.app/master/img/error.ico" alt="error" style="width: 96px !important; height: 96px !important;">
            </div>
            <h1 class="ctext">Whoops, there seems to be an error...</h1>
        </div>
        <div class="pad">
            <div class="ctext" style="font-size: xx-large;">
                The requested page either does not exist, or didn't load correctly.
            </div>
        </div>
    </slot>
</main>

<footer>
    
</footer>

<style>

    @media (prefers-color-scheme: light) {
        :root {
            font-size: 16px;
            text-align: left;
            color: black;
        }
    }

    @media (prefers-color-scheme: dark) {
        :root {
            font-size: 16px;
            text-align: left;
            color: white;
        }
    }

    main {
        flex: 1;
        display: flex;
        flex-direction: column;
        padding: 1rem;
        width: 100%;
        margin: 0 auto;
        box-sizing: border-box;
    }

    footer {
        display: flex;
        flex-direction: column;
        justify-content: stretch;
        align-items: stretch;
        padding: 40px;
        border-radius: 16px;
    }

    .textalign {
        text-align: center;
    }

    @media (min-width: 480px) {
        footer {
            padding: 0 40px 40px;
        }
    }

    h1 {
        font-size: 40px;
    }

    .ctext {
        text-align: center;
    }
</style>
