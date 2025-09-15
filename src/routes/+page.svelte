<main>
    <div class="flex flex-col items-stretch min-h-screen app">
        <Nav />
        <Base />
    </div>
    <div class="veil"></div>
</main>

<script>
    import "tailwindcss/tailwind.css"
    import Nav from '../components/nav.svelte'
    import Base from '../components/base.svelte'
</script>

<style global lang="postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    .app {
        background: url('/picture.png');
        background-position: right;
        background-size: contain;
        background-repeat: no-repeat;
        background-color: black;
    }
    .veil {
        position: absolute;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0,0,0,.6);
        z-index: 1;
    }
</style>