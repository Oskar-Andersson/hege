<main>
    <div class="flex flex-col items-stretch min-h-screen portfolio">
        <Nav link="/portfolio" />
        <div class="container mx-auto mt-12 mb-12">
            <img src="purple lineAsset 8.png" alt="decorative line" width="100%" />
        </div>

        <div class="container mx-auto grid grid-cols-1 lg:grid-cols-2 gap-4">
            <div>
                <div class="flex flex-col items-stretch">
                    <div class="flex justify-center"> 
                        <div class="my-2 items-stretch">
                            <div class="flex justify-center">Brochure with infographics</div>
                            <div>
                                <img class="mx-1 my-2 broch" src="/dog/A4 Brochure PSD Mockup.png" alt="Brochure">
                            </div>
                            <div class="flex justify-center mb-0">Mockup dog food, front and back</div>
                        </div>
                    </div>
                    <div class="grid grid-cols-2">                        
                            <div>                                
                                <div class="flex justify-end"><img class="mx-1" src="/dog/dog food frontAsset 6.png" alt="Rar Meshuggah med sverd"></div>
                            </div>
                            <div>                                
                                <div class="flex justify-start"><img class="mx-1" src="/dog/dog food backAsset 7.png" alt="Tulling med sverd på"></div>
                            </div>                        
                    </div>
                </div>                                
            </div>
            <div class="flex flex-col"> 
                <div class="flex flex-col flex-1">
                    <div class="flex justify-center align-items-center">Point of sale</div>
                    <div class="flex justify-center my-2"> <img class="my-2 doggostand" src="/dog/point of saleAsset 8.png" alt="Print poster"></div>
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
    .broch {
        width: 370px;
    }
    .doggostand {
        height: 277px;
    }
</style>