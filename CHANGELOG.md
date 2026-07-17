# v2.9.1 — 17-07-2026

- Primaire acties, waaronder **Constatering toevoegen**, gebruiken nu groen in plaats van rood.
- Rood blijft gereserveerd voor verwijder- en andere destructieve acties.
- De dubbele rand bij **Hoofdschakelaar** en **Voorbeveiliging** is verwijderd.
- Invoervelden binnen een eenheidsveld (zoals A) hebben nu één uniforme buitenrand.

# v2.8.1 — 17-07-2026

- De kaart **Locaties en installatieoverzicht** is verwijderd uit de projectgegevens.
- Nieuwe locaties kunnen alleen nog tijdens het toevoegen van een algemene constatering worden aangemaakt.
- Bij verdelers en omvormers kan een bestaande locatie nog steeds worden gekozen of aangepast.
- Bij verdelers en omvormers is de optie **Nieuwe locatie toevoegen** verwijderd.

# v2.8.0 — 17-07-2026

- Dashboardkaarten per verdeler en omvormer met locatie, status, constateringen, foto's, groepen/strings.
- Status per verdeler/omvormer: nog niet gestart, bezig of gereed.
- Projectvoortgang met gereed-percentage, aantallen constateringen en foto's.
- Verdelers en omvormers kunnen worden gedupliceerd; foto's worden bewust niet meegekopieerd.
- Foto's bij constateringen worden als compacte thumbnails getoond.
- Rapportcontrole controleert nu ook locaties, foto's en gereed-status van installatieonderdelen.

# v2.7.1
- Invoerveld voor nieuwe locaties is nu altijd zichtbaar en bruikbaar, ook op iPad/smalle schermen.
- Nieuwe locatie vanuit een verdeler, omvormer of algemene constatering wordt inline ingevoerd; geen browserprompt meer.
- De locatie van bestaande verdelers en omvormers kan direct via de keuzelijst worden gewijzigd.
- Nieuwe locaties worden centraal opgeslagen en direct geselecteerd.

## v2.5.2
- Zoekbalk toont nu direct zichtbare suggesties tijdens het typen.
- Zoeken op bijvoorbeeld “aardlek” laat resultaten gecategoriseerd onder de zoekbalk zien.
- Klikken op een suggestie vult de constatering automatisch in.
- Enter kiest het eerste zoekresultaat.

# v2.4.1
- Constatering toevoegen vereenvoudigd: de volledige lijst is direct zichtbaar.
- Zoekveld filtert dezelfde lijst zonder apart bibliotheekscherm.
- Eigen constatering kan direct onder de lijst worden geschreven.

# Changelog

## v1.2.2
- Rapportlayout voor verdeler- en omvormerfoto’s compact gehouden naast de gegevens.
- Constateringsfoto’s worden met hogere resolutie en minder compressie opgeslagen voor een duidelijker rapport.
- Omvormers zijn nu inklapbaar, net als verdelers.
- Kleine fout in het omvormer-contextlabel hersteld.
- PWA-cache verhoogd naar v1.2.2.

## v1.2.1
- Puntenberekening van Scope 8 compact in een 2×2-raster geplaatst.
- Label aangepast naar “Veiligheid installatie”.
- N.B. toegevoegd als directe keuze bij groep en locatie.
- Eigen waarden blijven mogelijk via “Anders…”.
- Verdelers zijn inklapbaar gemaakt voor een rustiger en korter formulier.
- Uitlijning, witruimte en kaartopmaak verder verbeterd.
- Foto’s in het rapport worden groter en zonder afsnijden weergegeven.
- Foto’s bij constateringen staan maximaal twee naast elkaar met fotonummer.
- PWA-cache verhoogd naar v1.2.1.

## v1.0.5
- Akkoord vóór aanvang inspectie verplaatst naar direct onder Projectgegevens op de Algemeen-pagina.
- Extra velden toegevoegd voor naam vertegenwoordiger, functie en datum akkoord.
- Bijlage 2 gebruikt nu automatisch dezelfde gegevens en handtekeningen; geen dubbele handtekeningpagina meer in het rapport.
- Compleetheidsstatus toegevoegd bij het akkoordblok.
- PWA-cacheversie verhoogd naar v1.0.5.

## v1.0.4
- Handtekeningen hernoemd naar akkoord vóór aanvang inspectie.
- Opdrachtgever tekent nu expliciet voor toestemming spanningsloos maken.
- Inspecteur tekent vóór aanvang van de inspectie.
- Ontvangsthandtekening na afloop bewust niet opgenomen.
- Bijlage 2 aangepast: geen akkoord op inspectieplan, omdat het inspectieplan extern vooraf wordt opgesteld.

## v1.0.3
- Handtekeningvelden toegevoegd voor inspecteur en opdrachtgever/vertegenwoordiger.
- Handtekeningen worden lokaal opgeslagen en opgenomen in het rapport.
- Compleetheidscontrole toegevoegd aan het rapportoverzicht.
- Rapport krijgt nu een aparte ondertekenpagina.
- PWA-cacheversie verhoogd naar v1.0.3.

## v1.0.2
- Projectgegevens uitgebreid.
- Meetinstrumentvelden uitgebreid.
- PWA-basis toegevoegd.

## v1.0.6 - Directie-demo UX
- Statusbalk toegevoegd met conceptstatus, opslaan en compleetheidspercentage.
- Rapportcontrole toegevoegd voordat een rapport definitief geprint wordt.
- Sticky tabnavigatie toegevoegd.
- iPad/touch-bediening verbeterd met grotere invoervelden en handtekeningvlakken.
- Waarschuwing toegevoegd bij verlaten met niet-opgeslagen wijzigingen.
- PWA-cache bijgewerkt naar v1.0.6.

## v1.1.0
- Nieuwe combinatie Scope 8-10-12 toegevoegd.
- Naamvelden voor verdelers en omvormers duidelijk zichtbaar gemaakt.
- iPad-bediening verbeterd met grotere touchvelden en responsieve invoer.
- Groepnummering wordt opnieuw berekend na verwijderen.
- Foto-invoer vraagt op ondersteunde mobiele apparaten direct om de achtercamera.
- Word-export toegevoegd naast PDF/print.
- Rapportopmaak en pagina-afbrekingen verbeterd.

## v1.2.3
- Datumvelden bij projectgegevens gelijkgetrokken met overige invoervelden.
- Invoer bij verdelers verder naar rechts uitgelijnd.
- Testknop-keuzelijst gecentreerd.
- Riso accepteert een lettertoetsenbord en zet V direct om naar >200.
- Nieuwe groepen nemen zowel In (A) als Ik (kA) over van de vorige groep.
- IΔA gewijzigd naar keuzelijst met 30, 100, 300 en 500 mA.
- Bij 'Anders' voor locatie van extra metingen verschijnt nu een normaal tekstveld in plaats van een pop-up.
- Titel op het voorblad naar het blauwe vlak verplaatst en de scheidslijn aangescherpt.
- Versienummer zichtbaar onderaan de applicatie.

## v1.2.4
- Nieuw dashboard met actief concept, compleetheid en lokaal archief.
- Sticky navigatie en klikbare voortgangsbalk per inspectieonderdeel.
- Automatisch opslaan versterkt bij wisselen van app/tab en afsluiten.
- Nieuwe groepen nemen In (A) en Ik (kA) over; overgenomen waarden hebben een kruisje om snel leeg te maken.
- Uitgebreidere rapportcontrole per verdeler en groep.
- Afronden en lokaal archiveren toegevoegd.
- Paginanummering aan rapportpagina's toegevoegd.

## v1.2.5
- Globale voortgangsbalk verwijderd.
- Sticky voortgang per invoerpagina toegevoegd; niet op Dashboard en Rapport.
- Algemeen-voortgang bovenaan geplaatst.
- Verdeelinrichtingen controleren velden, metingen, groepen en foto.
- Extra metingen controleren iedere regel volledig.
- Numerieke vlakken bij extra metingen zijn volledig aanklikbaar en openen het numerieke toetsenbord.
- Constateringen controleren classificatie, omschrijving en foto.
- Compleetheid verwijderd uit de dashboardstatistieken; blijft zichtbaar bij het actieve concept.
- Afronden & archiveren zet de inspectie daadwerkelijk in Afgeronde inspecties en start daarna een leeg concept.
- Foto-opslag blijft behouden bij archiveren.

## v1.2.6
- Blauwe contextlabels onder omvormers en verdeelinrichtingen verwijderd.
- IΔA (mA) kan nu op N.v.t. worden gezet; Δt wordt dan automatisch N.v.t. en uitgeschakeld.
- Per PV-string is een ligging toegevoegd: noord, noordoost, oost, zuidoost, zuid, zuidwest, west of noordwest.
- Ligging van PV-strings wordt ook in het rapport weergegeven.
- Voorblad bij print/PDF robuuster gemaakt met een absolute achtergrondreferentie, printkleurinstellingen en herstel na printen.

## v1.3.0 — Slimme inspectie-assistent (fase 2)
- Doorzoekbare constateringenbibliotheek met filters op scope en onderdeel.
- Automatische koppeling van IB22-groep, classificatie/kleur, omschrijving, hersteladvies en normreferentie.
- Flexibele locatiekoppeling aan ruimte, verdeler, groep, omvormer of PV-string.
- Maximaal drie foto's per constatering.
- Uitgebreide rapportcontrole op IB22, locatie, hersteladvies en foto's.
- IB22-gegevens, locatie, hersteladvies en normreferentie opgenomen in rapport.
- Scope 8 overal hernoemd naar Scope 8 PI.

## v2.3.0 — Slimme constateringenworkflow
- Zoekfunctie als primaire workflow met fuzzy zoeken.
- Favorieten en recent gebruikte constateringen.
- Fullscreen, horizontaal swipebare constateringenbibliotheek.
- Swipebare categorieën en constateringenkaarten.
- Automatische invulling van IB22-groep, classificatie, omschrijving, hersteladvies en normreferentie.
- Beheer van eigen constateringen met import en export als JSON.
- Contextuele suggesties op basis van inspectiescope en locatietype.
- Foto-assistent (beta) die relevante constateringen voorstelt; inspecteur blijft verantwoordelijk voor beoordeling.

## v2.4.2
- Het volledige popupmenu voor constateringen is verwijderd.
- De constateringenlijst, zoekfunctie en eigen invoer staan nu rechtstreeks op de pagina.
- Een gekozen of zelf geschreven constatering wordt direct toegevoegd.
- Locatie, foto's en opmerkingen kunnen daarna per constatering worden aangevuld door de kaart open te klappen.

## v2.5.0 — 17-07-2026
- Constateringenpagina teruggebracht naar de eenvoudige, vertrouwde formulierindeling.
- Zoekveld filtert de normale bibliotheekdropdown.
- Optie “Overige / eigen constatering” toegevoegd voor vrije invoer.
- Gekoppelde verdeelinrichting, classificatie, aanvulling en foto's blijven direct zichtbaar.
- Geen pop-up, wizard of apart keuzescherm meer.

## v2.5.1
- Zoeken in de constateringenbibliotheek hersteld en robuuster gemaakt.
- Zoekopdrachten met meerdere woorden werken nu token voor token.
- Zoeken kijkt ook naar categorie, trefwoorden, omschrijving, advies, norm en IB22-groep.
- Bestaande constateringen staan opnieuw gegroepeerd per categorie in de keuzelijst.
- Enter kiest het eerste passende zoekresultaat.

## v2.6.0 — Gebruiksgemak constateringen
- Zoekveld afgerond en gelijkgetrokken met overige invoervelden.
- Compactere veldafstand en duidelijkere focusweergave.
- Recente constateringen zichtbaar bij een leeg zoekveld.
- Na toevoegen korte bevestiging en automatische focus terug naar zoeken.
- Samenvatting met aantallen constateringen, foto's en gekoppelde verdeelinrichtingen.
- Compactere acties voor bewerken en verwijderen in het overzicht.
- Laatst gekozen verdeelinrichting blijft geselecteerd voor de volgende constatering.

## v2.9.2 — 17-07-2026
- Installateur verwijderd uit Projectgegevens.
- Kalibratievelden sluiten weer netjes aan binnen het raster.
- Navigatieknoppen Vorige/Volgende toegevoegd onderaan alle inspectietabs.
- Algemeen heeft alleen een Volgende-knop en gaat niet terug naar Dashboard.
- Nieuwe locaties worden automatisch opgeslagen bij Enter of verlaten van het veld; aparte Toevoegen-knop verwijderd.
- Een fout ingevoerde, ongebruikte locatie kan worden verwijderd.
- Dashboard toont geen installatievoortgang, percentages of aangemaakte verdeelkasten meer.
- Dashboard beperkt tot aantallen verdeelinrichtingen, omvormers, afgeronde inspecties, constateringen en foto’s.
- Objectstatus vereenvoudigd tot Bezig en Gereed; nieuwe objecten starten als Bezig.

## v2.9.3 — 17-07-2026
- Dashboard vereenvoudigd tot Nieuwe inspectie, Conceptinspecties en Afgeronde inspecties.
- Losse knop 'Actief concept openen' en dashboardstatistieken verwijderd.
- Het actuele concept staat als aanklikbare inspectie in de lijst Conceptinspecties.
- Vorige/Volgende en alle andere tabwisselingen openen de nieuwe pagina bovenaan.
