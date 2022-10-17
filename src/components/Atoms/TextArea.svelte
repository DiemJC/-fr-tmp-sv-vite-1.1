<script>
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let bordered = false;
    export let ghost = false;
    export let disabled = false;
    export let placeholder = "Bio";
</script>

<textarea class="textarea w-full"

    class:textarea-primary={primary}
    class:textarea-secondary={secondary}
    class:textarea-accent={accent}
    class:textarea-info={info}
    class:textarea-success={success}
    class:textarea-warning={warning}
    class:textarea-errpr={error}
    class:textarea-bordered={bordered}
    class:textarea-ghost={ghost}
    placeholder={placeholder}
    data-theme="light"
    {disabled}
>
    
</textarea>



