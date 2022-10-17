<script>
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;
    export let disabled = false;
    export let checked = false;

</script>

<input type="checkbox" class="toggle"
    class:toggle-primary={primary}
    class:toggle-secondary={secondary}
    class:toggle-accent={accent}
    class:toggle-lg={large}
    class:toggle-md={medium}
    class:toggle-sm={small}
    class:toggle-xs={tiny}
    bind:checked
    {disabled}
>


<!-- Need to predefine checked status -->