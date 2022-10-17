<script>
    export let primary = false;
    export let primaryBG = false;
    export let primaryBorder = false;
    export let value = 50;

</script>

<div class="radial-progress"
    class:text-primary={primary}
    class:bg-primary={primaryBG}
    class:border-primary={primaryBorder}
    style:--value={value}
>
<slot></slot>
</div>

