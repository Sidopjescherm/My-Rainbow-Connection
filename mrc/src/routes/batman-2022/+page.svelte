<script>
        import { onMount } from 'svelte';

    /** @type {{ data: import('./$types').PageData }} */
</script>
<nav>
    <ul>
        <li><a href="#batman">BATMAN</a></li>
        <li><a href="#characters">CHARACTERS</a></li>
        <li><a href="#vehicles">VEHICLES</a></li>
        <li><a href="#city">CITY</a></li>
        <li><a href="#story">STORY</a></li>
    </ul>
</nav>
<section id="page">
    <section id="batman">
        <article>
            <picture>
                <!-- here will be a picture of the Batman -->
            </picture>
            <h1>BATMAN</h1>
            <p>
                Bruce Thomas Wayne is a reclusive orphaned billionaire, 
                the current owner of Wayne Enterprises, the direct heir of the Wayne Family, and the heroic figure 
                known infamously as <strong>the Batman.</strong>
            </p>
            <p>
                After the ruthless murder of his parents by the hands of an unknown mugger, 
                Wayne angrily swore vengeance against all criminals, an oath tempered by a sense of 
                justice for which he trained himself physically and intellectually, all to become Gotham 
                City's guardian and protector, using a lethal combination of mental mastery, martial arts prowess,
                 physical strength, and expert technology to fight crime on Gotham's nights, aided by his wise mentor and 
                 butler Alfred Pennyworth, the incorruptible GCPD Lieutenant Jim Gordon, and morally ambiguous thief Selina Kyle, 
                 his love interest.
            </p>
        </article>
    </section>

    <section id="characters">
        <h2>CHARACTERS</h2>
        <article>
            <a href="catwoman">CATWOMAN</a>
            <a href="riddler">RIDDLER</a>
            <a href="jim-gordon">JIM GORDON</a>
        </article>
    </section>

    <section id="vehicles">
        <h3>VEHICLES</h3>
        <article>
            <picture>
                <!-- here there will be a picture of the batmobile -->
            </picture>
            <p>The batmobile</p>
        </article>
    </section>

    <section id="city">
        <h4>CITY</h4>
        <article>
            <p>Gotham City</p>
        </article>
    </section>

    <section id="story">
        <h5>STORY</h5>
        <article>
            <p>The story of The Batman</p>
        </article>
    </section>
</section>