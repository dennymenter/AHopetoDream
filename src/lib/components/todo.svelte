<script>
    import "/src/css/images.css"

    export let title = "";
    export let desc = "";
    export let status = "";

</script>


<div class="w-1/3 border-2 border-black rounded-lg  drop-shadow-2xl bg-slate-200 m-5 p-5">
    <div class="">Todo: {title}</div>
    <div>{desc}</div>
    <div>

        {#if status=="done"}
        <div class="gg-menu test">DONE</div>
        <i class="gg-menu"></i>
        {:else}
        IN PROGRESS
        {/if}

    </div>
</div>