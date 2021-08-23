<script>
    import { onMount } from 'svelte'
    import { fly, fade } from 'svelte/transition'

    let show = false;
    onMount(() => {
        show = true;
    })
</script>

<style>
    div {
        position: relative;
    }
</style>


<div in:fade out:fade>
    <slot></slot>
</div>