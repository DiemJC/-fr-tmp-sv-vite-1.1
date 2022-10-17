<script>
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;
</script>

<kbd class="kbd"
    class:kbd-lg={large}
    class:kbd-md={medium}
    class:kbd-sm={small}
    class:kbd-xs={tiny}
>
<slot></slot>    
</kbd>