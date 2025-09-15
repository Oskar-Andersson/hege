<main>
    <div class="flex flex-col items-stretch min-h-screen portfolio">
        <Nav />
        <div class="container mx-auto mt-12 mb-12">
            <img src="purple lineAsset 8.png" alt="decorative line" width="100%" />
        </div>
        <Portfoliolist />
    </div>
</main>

<script>
    import "tailwindcss/tailwind.css"
    import Nav from '../components/nav.svelte'
    import Portfoliolist from '../components/portfoliolist.svelte'
</script>

<style lang="postcss">
    .portfolio {
        background-image: none;
        background-position: right;
        background-size: contain;
        background-repeat: no-repeat;
        background-color: black;
    }
</style>