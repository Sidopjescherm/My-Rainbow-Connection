<script>
        import { onMount } from 'svelte';
        import '$lib/batman.css';
        const batpat2022 = '/images/batman-2022.png';
        const batmobile = '/images/batmobile-the-batman-2022.jpg';
        const batcycle = '/images/Batcycle.webp';
        const gotham = '/images/Gotham_Square.webp';

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
                <img src={batpat2022} alt="Batman's upper body stands with his head looking down. Red light shines from above." width="200">
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
                <img 
                    src={batmobile} 
                    alt="" 
                    width="300"
                    loading="lazy"
                >
            </picture>
            <p>
                The Batmobile is the main vehicle used by Batman. It is a modified 
                muscle car custom built by Bruce Wayne, containing multiple gadgets as 
                well as being heavily armored and fire resistant. The Batmobile helps aid Batman in his war on crime.
            </p>
        </article>

        <article>
            <picture>
                <img 
                    src={batcycle} 
                    alt="" 
                    width="300"
                    loading="lazy"
                >
            </picture>
            <p>
                The Batcycle is the Batman&#x2019s sleekest mode of transport, 
                and perfect for racing through Gotham&#x2019s streets at breakneck speeds.         
            </p>
        </article>
    </section>

    <section id="city">
        <h4>CITY</h4>
        <article>
            <picture>
                <img 
                    src={gotham} 
                    alt="Gotham City skyline at night. A bustling street with neon lights and towering skyscrapers." 
                    width="300"
                    loading="lazy"
                >
            </picture>
            <p>
                <strong>Gotham City</strong> is a bustling, 
                dark city located in the U.S. state of New Jersey. In addition to 
                being the home and main base of operations for the heroic figure known as the Batman, 
                Gotham is also rife with corruption, poverty, vermin infestations, pollution 
                and numerous crime waves. The city's motto is "Sic Parvis Magna."</p>
        </article>
    </section>

    <section id="story">
        <h5>STORY</h5>
        <article>
            <p>
                On Halloween night, Gotham City mayor Don Mitchell, Jr. is brutally 
                murdered by a serial killer calling himself the Riddler. Billionaire Bruce Wayne, 
                who has operated in Gotham for two years as the vigilante Batman, roams the streets
                of Gotham as the Drifter, a third persona of Bruce, searching criminals so he can stop them. 
                The Bat Signal is on, and the Batman's symbol can be seen in the skies. Criminals of all kinds
                look at the symbol as a bad omen, and tremble in fear looking at the shadows that pervades 
                the city thinking that Batman may be hiding in them, waiting to strike them at last. A small 
                gang of punks tries to rob an innocent man, but they are stopped by Batman. After dealing with the gang, 
                the vigilante goes to the scene of the mayor's murder and alongside the Gotham City Police Department. 
                Lieutenant Jim Gordon discovers that the Riddler left a message for Batman. GCPD commissioner Pete Savage 
                berates Gordon for allowing Batman to enter the crime scene and forces him to leave. In a press conference, 
                Commissioner Savage confirms to the media that the mayor is dead and promises that he will capture the killer.
                At a distance, Bruce, as the Drifter, watches the press conference, and then drives back to the Batcave on his
                Batcycle. There, Bruce writes a diary and watches the footage recorded from his contact lens to help with his
                memory, which is weakening because of his non-stop night patrols. The Riddler kills Savage shortly afterward,
                leaving another message for Batman and sending a video of his death to Gotham news media.
            </p>

            <p>
                Batman and Gordon discover that the Riddler left a thumb drive in Mitchell's car; it contains images 
                of Mitchell with a woman, Annika, at the Iceberg Lounge, a club operated by mobster Carmine Falcone's 
                lieutenant Oz Cobb aka the Penguin. Batman questions the Penguin, who claims to know nothing, but notices that 
                Selina Kyle, Annika's roommate and girlfriend, works there as a waitress. He follows Selina to Mitchell's house 
                where, after a brief scuffle, they discover Annika's passport in a safe. When Annika disappears, 
                Batman sends Selina back to the Iceberg Lounge to search for answers. Through Selina, Batman discovers 
                Gotham District Attorney Gil Colson is on Falcone's payroll, but Selina shuts off communication when Batman
                presses her about her relationship with Falcone.
            </p>

            <p>
                The Riddler abducts Colson, straps a time bomb to his neck, and sends him to interrupt Mitchell's funeral. 
                When Batman arrives at the scene, the Riddler calls him via Colson's phone. He threatens to detonate the bomb 
                if Colson cannot answer three riddles; Batman helps Colson answer the first two, but Colson refuses to answer 
                the third—name the "rat" who gave the GCPD information that led to a historic drug bust ending mobster 
                Salvatore Maroni ‘s operation—so the Riddler kills him. Batman and Gordon deduce that the informant may be 
                the Penguin and track him to a drug deal. They discover that Maroni's operation never actually ended and many 
                GCPD officers are involved in it. Their plan to interrogate the Penguin is interrupted when Selina arrives 
                to steal drug money and inadvertently exposes them. As the Penguin flees, Selina discovers Annika's corpse in
                a car trunk.
            </p>

            <p>
                Batman captures the Penguin after chasing him in the Batmobile, 
                but learns that he was not the informant. Batman and Gordon go to investigate the ruins of an orphanage 
                operated by Bruce's parents Thomas and Martha. They learn that the Riddler was a resident at the orphanage 
                and holds a grudge against Thomas; as Thomas is dead, he has decided to target Bruce. Bruce's butler and 
                caretaker, Alfred Pennyworth, is hospitalized after opening a letter bomb addressed for Bruce. Selina reveals 
                that Falcone is her father and that he neglected her. The Riddler then leaks evidence alleging that Thomas,
                who was running for mayor when he was murdered, hired Falcone to kill a journalist for threatening to reveal 
                embarrassing details about Martha's history of mental illness.
            </p>

            <p>
                A devastated Bruce, who grew up believing his father was a morally upstanding man, confronts Falcone and Alfred. 
                Alfred confirms that Thomas asked Falcone to intimidate the journalist, but decided to turn Falcone over to the 
                police after learning of the murder; he surmises that Falcone had Thomas and Martha killed to prevent this but 
                also admitted it could've been a random mugger. Selina then signals Batman and Gordon and tells them that Falcone 
                strangled Annika after Mitchell told her that he was the informant, and resolves to kill him. Batman and Gordon 
                arrive at the Iceberg Lounge in time to stop her and arrest Falcone, but as he's being led out of the club the
                Riddler snipes him from a nearby building. Unmasked as unassuming forensics scientist Edward Nashton, the Riddler
                is arrested and incarcerated in Arkham State Hospital.
            </p>

            <p>
                After arresting Nashton, Batman and the GCPD search Riddler's apartment for evidence and they discover his 
                real name is Edward Nashton and he is a forensic accountant at KTMJ who had been planning 
                to expose Gotham's hidden corruption for years, before asking Batman to visit him at Arkham. At Arkham,
                Nashton says he was envious of the sympathy Bruce received after his parents' murder while he was ignored, 
                and wanted to partner with Batman and become a similar masked vigilante. After Batman angrily rejects Nashton, 
                he reveals that he has placed numerous car bombs around Gotham. The bombs destroy Gotham's Seawall and flood the
                city. Batman discovers that Nashton cultivated an internet following that plans to assassinate mayor-elect 
                Bella Reál in the ensuing chaos when they retreat to Gotham's downtown sports arena. Nashton's followers have 
                infiltrated the arena and attempt to kill Reál, but Batman and Selina manage to stop them. As Batman begins to 
                aid in recovery efforts becoming a beacon of hope for the survivors, Selina resolves to leave Gotham, deeming it 
                beyond saving, while Penguin overlooks Gotham from the Shoreline Lofts window, planning taking Falcone's place 
                as the Kingpin of Gotham.
            </p>

            <p>
                Back at Arkham, Nashton is met by a fellow deranged inmate who commends him on the scope of 
                his plan to flood Gotham and publicly expose it's corruption. He then provides a riddle regarding 
                the value of friendship as the two of them share a maniacal laugh in their respective cells. While at
                 Maria Kyle's tomb, Batman and Selina bid farewell as Selina is leaving Gotham for Blüdhaven. 
                 She asks Batman to come with her but she knows he's needed in Gotham. The two go their separate ways 
                 and then leave on their motorcycles.
            </p>
        </article>
    </section>
</section>