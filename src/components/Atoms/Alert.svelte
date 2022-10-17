<script>
    export let shadowlg = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
</script>

<div class="alert"
    class:shadowlg={shadowlg}
    class:alert-info={info}
    class:alert-success={success}
    class:alert-warning={warning}
    class:alert-error={error}
>
<slot></slot>
</div> 



<!-- Icons need to be implemented -->