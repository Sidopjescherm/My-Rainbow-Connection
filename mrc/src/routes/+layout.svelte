<script>
    /** @type {import('./$types').LayoutProps} */
    let { data, children } = $props();

    import "$lib/global.css" 
</script>

<header>
    <nav>
        <a href="/">Home</a>
        <a href="/experiments">Experiments</a>
        <a href="/projects">Projects</a>
    </nav>
</header>
{@render children()}

<style>
    header {
        display: flex;
        justify-content: space-evenly;
        flex-wrap: wrap;
    }

    nav {
        display: flex;
        gap: 1rem;
    }
</style>