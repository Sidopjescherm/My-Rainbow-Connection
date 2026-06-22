<script>
    /** @type {import('./$types').PageProps} */
    let { data } = $props();
</script>

<main>
    <h1>Projects</h1>

    <article>
        <a href="https://oncollaboration.dev.fdnd.nl/">
            <h2>Oncollaboration</h2>
        </a>

        <p>
            Oncollaboration is a platform for doctors to watch webinars and
            ask questions about treatment of cancer patients and the way diffrent 
            kinds of tumors start to grow.
        </p>
    </article>

    <article>
        <a href="https://adconnect.dev.fdnd.nl/">
            <h2>ADconnect</h2>
        </a>

        <p>
            ADconnect is a platform for teachers of Associate Degress to come
            together and discuss certain topics. Though it is not only a platform to discuss ideas,
            it's also a platform that gives information about AD's and serves as a main
            way of communicating the new AD-dag 
        </p>
    </article>

    <article>
        <a href="https://air-pollution-africa.netlify.app/">
            <h2>Air-pollution Africa</h2>
        </a>

        <p>
            Air-pollution Africa is a way to monitor the pollution of air in the city
            of Kumasi, Ghana. This project was started due to false readings from sattelite
            pictures and so this now covers the correct amounts of pollution!   
        </p>
    </article>
</main>

<style>
    main {
        display: flex;
        flex-direction: column;    
        gap: 2rem;
    }

    article {
        border:dotted 5px var(--divided-red);
        padding: 1rem;
    }
</style>