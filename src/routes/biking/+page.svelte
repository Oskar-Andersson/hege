<main>
    <div class="flex flex-col items-stretch min-h-screen portfolio">
        <Nav link="/portfolio" />
        <div class="container mx-auto mt-12 mb-12">
            <img src="purple lineAsset 8.png" alt="decorative line" width="100%" />
        </div>
         <div class="container mx-auto grid grid-cols-1 lg:grid-cols-2 gap-4">
            <div>
                <a href="/biking/photo 2Asset 4.png" target="_blank">
                    <img src="/biking/photo 2Asset 4.png" alt="Screenshot with mock ipad">
                </a>
            </div>
            <div>
                <a href="/biking/Hanne 3Asset 3.png" target="_blank">
                    <img src="/biking/Hanne 3Asset 3.png" alt="Hanne på cykkel">
                </a>
            </div>
        </div>
    </div>
</main>

<script>
    import "tailwindcss/tailwind.css"
    import Nav from '../components/nav.svelte'
</script>

<style lang="postcss">
    .portfolio {
        background-image: none;
        background-position: right;
        background-size: contain;
        background-repeat: no-repeat;
        background-color: black;
    }
    img {
        width: 100%;
    }
    
</style>