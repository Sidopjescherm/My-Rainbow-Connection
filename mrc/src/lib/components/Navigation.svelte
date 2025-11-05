<header>
    <a href="#menu" class="menu-toggle">MENU</a>
    <nav id="menu">
        <a href="#" class="menu-close">CLOSE</a>
        <ul>
            <li><a href="#batman">BATMAN</a></li>
            <li><a href="#characters">CHARACTERS</a></li>
            <li><a href="#vehicles">VEHICLES</a></li>
            <li><a href="#city">CITY</a></li>
            <li><a href="#story">STORY</a></li>
        </ul>
    </nav>
</header>

<style>
    header {
        padding: 0.5em;
        position: sticky;
        top: 0;
        z-index: 100;

        background-color: var(--accent-color-yellow);
        @media (prefers-color-scheme: dark) {
            background-color: var(--neutral-color-darkest);
        }

        border-bottom: 0.25rem solid var(--primary-color-red);
    }
    nav {
        position: fixed;
        top: 0;
        right: -100%;
        width: 100%;
        transition: right 0.3s ease;
        display: flex;
        flex-direction: column;
        padding: 1em;

        background-color: var(--accent-color-yellow);
        @media (prefers-color-scheme: dark) {
            background-color: var(--neutral-color-darkest);
        }

        border-bottom: 0.25rem solid var(--primary-color-red);
    }

    #menu:target {
        right: 0;
    }

    .menu-close {
        position: absolute;
        top: 1em;
        right: 1.2em;
    }
    
    ul {
        list-style: none;
        gap: 1rem;
    }

    a{
        color: var(--primary-color-darkest);
        @media (prefers-color-scheme: dark){
            color: var(--primary-color-red);
        }
        text-decoration: none;
        background-color: var(--accent-color-yellow);
        @media (prefers-color-scheme: dark){
            background-color: var(--neutral-color-darkest);
        }
    }
</style>