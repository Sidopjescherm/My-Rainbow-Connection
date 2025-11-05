<script>
        import { onMount } from 'svelte';
        import '$lib/batman.css';
        
        import Batman from '$lib/components/Batman.svelte';
        import Characters from '$lib/components/Characters.svelte';
        import Vehicles from '$lib/components/Vehicles.svelte';
        import City from '$lib/components/City.svelte';
        import Story from '$lib/components/Story.svelte';

    /** @type {{ data: import('./$types').PageData }} */
</script>

<svelte:head>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
    </style>
</svelte:head>

<section id="page">
    <section id="batman">
        <Batman />
    </section>

    <section id="characters">
        <Characters />
    </section>

    <section id="vehicles">
        <Vehicles />
    </section>

    <section id="city">
        <City />
    </section>

    <section id="story">
        <Story />
    </section>
</section>

<style>
    #page {
        background-color: var(--accent-color-yellow);
        @media (prefers-color-scheme: dark) {
            background-color: var(--neutral-color-darkest);
        }
    }
</style>