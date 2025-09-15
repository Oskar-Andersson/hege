<main>
    <div class="flex flex-col items-stretch min-h-screen portfolio">
        <Nav link="/portfolio" />
        <div class="container mx-auto mt-12 mb-12">
            <img src="purple lineAsset 8.png" alt="decorative line" width="100%" />
        </div>
         <div class="container mx-auto grid grid-cols-1 lg:grid-cols-2 gap-4">
            <div>
                <div class="flex flex-col items-stretch">
                    <div class="flex justify-center">Poster for print version</div>
                    <div class="flex justify-center my-2"> <img class="my-2" src="/studio/front posterAsset 10.png" alt="Print poster"></div>
                </div>                
            </div>
            <div>
                <div class="flex flex-col items-stretch">
                    <div class="flex justify-center">Studio Pictures</div>
                    <div class="flex justify-center"> 
                        <div class="my-2">
                            <div>
                                <img class="mx-1 my-2" src="/studio/photo 1Asset 5.png" alt="Hyl med sverd">
                            </div>
                            <div>
                                <img class="mx-1 my-2" src="/studio/photo 2Asset 6.png" alt="Sint fjes">
                            </div>
                        </div>
                        <div class="my-2">
                            <div>
                                <img class="mx-1 my-2" src="/studio/photo 3Asset 7.png" alt="Rar Meshuggah med sverd">
                            </div>
                            <div>
                                <img class="mx-1 my-2" src="/studio/photo 4Asset 8.png" alt="Tulling med sverd på">
                            </div>

                        </div>

                    </div>
                </div>                
                
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
        color: white;
    }
</style>