<script>
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let max = "100"
    export let value = "50"
</script>

<progress class="progress"
    class:progress-primary={primary}
    class:progress-secondary={secondary}
    class:progress-accent={accent}
    class:progress-info={info}
    class:progress-success={success}
    class:progress-warning={warning}
    class:progress-error={error}
    value={value}
    max={value ? max: ""}
>  
</progress>




<!-- Value of the progress bars needs to be specified, as of now, only styling is applied -->