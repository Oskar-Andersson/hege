<script>
    export let link = '/portfolio';
</script>
<div>
<article class="container mx-auto my-8 grid grid-cols-1 lg:grid-cols-2 gap-12" style="z-index: 100;">
    <div class="gap-4 flex flex-col align-content-left mx-4">
           <div class="container"><slot name="left1"></slot></div>
           <div class="container"><slot name="left2"></slot></div>
           <div class="container"><slot name="left3"></slot></div>
        </div>
    <div class="flex-1 grid gap-4 flex flex-row justify-items-center">
        <div class="gap-4 flex flex-col">
            <div><slot name="right"></slot></div>
            <div class="flex justify-center"><a href="{link}"><img class="more" alt="Read more button" src="view more buttonAsset 6.svg"></a></div>
        </div>            
    </div>  
</article>        
<article class="container mx-auto flex flex-row gap-12" style="z-index: 100;">
</article>
</div>

<style lang="postcss">
    .more {
        width: 120px;
        cursor: pointer;      
    }
</style>