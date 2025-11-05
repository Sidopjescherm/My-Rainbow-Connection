<script>
    /** @type {import('./$types').LayoutProps} */
    let { data, children } = $props();
    import Navigation from '$lib/components/Navigation.svelte';
</script>
<Navigation />

{@render children()}