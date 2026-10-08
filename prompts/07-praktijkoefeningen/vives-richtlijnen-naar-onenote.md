# VIVES-richtlijnen omzetten naar een OneNote-invulsjabloon

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Van VIVES-richtlijnen naar een OneNote-invulsjabloon voor een AI-usecase |
| Categorie | 07 – Praktijkoefeningen |
| Versie | 1.0 |
| Status | beschikbaar |
| Prompttaal | nl |
| Uitvoertaal | nl |
| AI-platform | AI-assistent met toegang tot het pdf-document en een OneNote-koppeling |
| Laatst bijgewerkt | 2026-10-09 |

## Doel

Een aangeleverd VIVES-richtlijnendocument omzetten naar een daadwerkelijk aangemaakt OneNote-notitieblok met secties, schrijfvragen, invultabellen en eindcontrole voor een nog te bepalen AI-usecase.

## Wanneer gebruiken?

Gebruik deze masterprompt om een nieuw invulsjabloon te maken vanuit de oorspronkelijke opleidingsrichtlijnen. Het uitgangspunt voor de richtlijnen 2025–2026 is 14 secties en 45 pagina’s; de inhoud van de aangeleverde bron blijft leidend.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{VIVES-pdf-document}}` | Ja | Voeg het oorspronkelijke pdf-document toe of maak het toegankelijk voor de AI-assistent | Richtlijnen AI use case 2025–2026 |
| `{{notitiebloknaam}}` | Nee | Unieke naam voor het nieuwe OneNote-notitieblok | AI use case - Invulsjabloon |

## Prompt

Kopieer de volledige tekst uit het onderstaande codeblok en vul de parameters in.

```text
# Masterprompt – Van VIVES-richtlijnen naar een OneNote-invulsjabloon voor een AI-usecase

## Rol

Je bent een expert in AI-businesscases, onderwijsontwerp, enterprise-architectuur en Microsoft OneNote. Je vertaalt opleidingsrichtlijnen naar een praktisch invulsjabloon waarmee een gebruiker een samenhangende, onderbouwde AI-usecase kan schrijven.

## Opdracht

Lees het aangeleverde VIVES-pdf-document met de richtlijnen voor een AI-usecase volledig.

**Maak vervolgens daadwerkelijk een nieuw Microsoft OneNote-notitieblok**, met alle benodigde secties en invulpagina’s. Lever niet uitsluitend een voorstel of inhoudsopgave op.

Het onderwerp en de organisatie van de AI-usecase zijn nog niet bepaald. Laat deze gegevens invulbaar.

## Parameters

- Brondocument: `{{VIVES-pdf-document}}`
- Naam van het nieuwe notitieblok: `{{notitiebloknaam}}`
- Taal: Nederlands
- Onderwerp van de case: nog te bepalen
- Organisatie: nog te bepalen

Gebruik als standaardnaam **AI use case - Invulsjabloon** wanneer geen naam is opgegeven.

## 1. Controleer en analyseer de bron

1. Lees het oorspronkelijke pdf-document volledig. Gebruik eerdere samenvattingen alleen als aanvullende context.
2. Identificeer:
   - Inhoudelijke vereisten.
   - Verplichte en optionele modellen en analyses.
   - Deelopdrachten en hun relatie tot de eindcase.
   - Vormvereisten, omvang en beoordeling.
   - Vereiste interviews, vragenlijsten en bewijsstukken.
   - Verwijzingen naar afzonderlijke templates en bijlagen.
3. Onderscheid expliciet:
   - **Verplicht volgens de bron.**
   - **Optioneel volgens de bron.**
   - **Aanbevolen uitwerking voor het invulsjabloon.**
4. Neem deadlines uit het brondocument niet automatisch over. Vermeld het academiejaar van de bron en laat actuele deadlines invulbaar.
5. Vermeld welke aanvullende documenten niet beschikbaar zijn. Verzin hun inhoud niet.
6. Leg vast welke bronvereiste op welke OneNote-pagina wordt behandeld. Gebruik daarbij de documentpagina’s als bronverwijzing en onderscheid die zo nodig van gedrukte paginanummers.

De structuur hieronder is een uitgangspunt. Pas deze aan wanneer de daadwerkelijke bron andere vereisten bevat. Presenteer een eigen hoofdstukindeling nooit als een officieel voorgeschreven VIVES-format.

## 2. Maak het OneNote-notitieblok

Gebruik de beschikbare OneNote-koppeling.

- Controleer eerst de bestaande notitieblokken.
- Maak een nieuw notitieblok met de opgegeven naam.
- Voorkom onbedoelde duplicaten. Bij een naamconflict: kies een duidelijke unieke naam of vraag welke bestemming bedoeld is.
- Gebruik de werkelijk teruggegeven notebook-, sectie- en pagina-ID’s.
- Maak genummerde secties en genummerde pagina’s, zodat de volgorde ook bij alfabetisch sorteren herkenbaar blijft.
- Schrijf eenvoudige OneNote-compatibele HTML, met een expliciete paginatitel, koppen, alinea’s, lijsten en tabellen.
- Wijzig geen bestaande notitieblokken en deel het nieuwe notitieblok niet, tenzij daar afzonderlijk om is gevraagd.

## 3. Gebruik deze basisstructuur

Streef voor de VIVES-richtlijnen 2025–2026 naar onderstaande **14 secties en 45 pagina’s**. Inhoudelijke volledigheid en brongetrouwheid gaan boven dit aantal.

### 00 Start en schrijfwijzer

- 00.1 Lees mij en gebruik van het sjabloon
- 00.2 Casefiche en voortgang
- 00.3 Vereisten- en eindcontrole

### 01 Organisatie en strategie

- 01.1 Organisatie en strategische context
- 01.2 WHY en WHY NOW

### 02 Probleem en projectvoorstel

- 02.1 Probleem, doelen en scope
- 02.2 Projectvoorstel en mandaat
- 02.3 Stakeholders en behoeften

### 03 Businesscase en waarde

- 03.1 Route to Value
- 03.2 Kosten, baten en ROI
- 03.3 Succescriteria en aannames

### 04 Data en AI

- 04.1 Drie DAMA-topics
- 04.2 Databronnen en data-architectuur
- 04.3 Datakwaliteit en informatiebetrouwbaarheid
- 04.4 AI-technologie en oplossingskeuze

### 05 KPI’s en dashboard

- 05.1 KPI-register en meetplan
- 05.2 Dashboard en visualisaties

### 06 Architectuur en processen

- 06.1 Strategie en businessarchitectuur
- 06.2 Huidig en toekomstig proces
- 06.3 Make-or-buy en migratiepad
- 06.4 Motivation en Decision

### 07 Requirements

- 07.1 Businessrequirements
- 07.2 Functionele requirements of user stories
- 07.3 MoSCoW en traceerbaarheid
- 07.4 Niet-functionele requirements

### 08 Juridische analyse

- 08.1 Relevante wetgeving en AI-verordening
- 08.2 Eén concrete juridische uitdaging

### 09 Ethiek en betrouwbare AI

- 09.1 Vier stakeholders en interview
- 09.2 Waarden en handelingsopties
- 09.3 Trustworthy AI-zelfevaluatie
- 09.4 Reflectie op juridische en ethische analyse

### 10 Mens en duurzaamheid

- 10.1 Sociologische en organisatorische impact
- 10.2 Readiness en change management
- 10.3 Sustainable AI in business

### 11 Implementatie en risico’s

- 11.1 Aanpak, roadmap en resources
- 11.2 Risicoregister
- 11.3 Evaluatie en operationalisering

### 12 Synthese en verdediging

- 12.1 Managementsamenvatting
- 12.2 Conclusies en aanbevelingen
- 12.3 Presentatie en juryvragen

### 13 Bronnen, bijlagen en projectbeheer

- 13.1 Bibliografie en bronregister
- 13.2 Transparante vermelding van genAI
- 13.3 Bijlagen en modellen
- 13.4 Planning, coaching en besluiten
- 13.5 Eindredactie en indiening

## 4. Vul iedere pagina met een bruikbaar schrijfsjabloon

Maak inhoudelijke invulpagina’s, geen lege pagina’s met alleen een titel.

Elke pagina bevat:

### A. Status en beheer

- Status volgens de richtlijnen: verplicht, optioneel of aanbevolen.
- Schrijfstatus: Open / In uitvoering / Gereed.
- Eigenaar: `[in te vullen]`.
- Laatst bijgewerkt: `[in te vullen]`.
- Bronverwijzing naar de relevante richtlijnpagina’s, waar toepasselijk.

### B. Doel van de pagina

Beschrijf kort wat de schrijver hier moet uitwerken en hoe dit bijdraagt aan de AI-usecase.

### C. Schrijfvragen en instructies

Formuleer concrete vragen die rechtstreeks aansluiten bij het onderwerp. Geef relevante omvangs- of bewijsvereisten mee.

### D. Invultabel

Maak een passende tabel met betekenisvolle kolommen en voorbereide rijen. Gebruik `[in te vullen]` voor onbekende inhoud.

Voorbeelden:

- KPI’s: ID, definitie en formule, databron, nulmeting, streefwaarde, termijn, eigenaar en meetfrequentie.
- Requirements: ID, beschrijving, stakeholder, gekoppeld doel, acceptatiecriteria en MoSCoW-prioriteit.
- Risico’s: ID, risico, kans, impact, maatregel, eigenaar en restrisico.
- Roadmap: fase, activiteit, resultaat, eigenaar, middelen, termijn en besluitcriterium.
- Ethiek: waarde, handelingsoptie voor technologie, omgeving en gebruiker, en motivatie.
- Bronnen: ID, auteur, jaar, titel, vindplaats, APA-vermelding en ondersteunde claim.

### E. Uitgewerkte tekst

Voeg ruimte toe voor de samenhangende tekst die later in het einddocument kan worden verwerkt.

### F. Bewijs, aannames en open vragen

Voorzie afzonderlijke invulvelden voor:

- Bronnen en bewijsstukken.
- Aannames en onzekerheden.
- Open vragen.
- Vervolgacties.

### G. Controlepunt

Sluit af met een korte inhoudelijke controle: zijn de vragen beantwoord, de keuzes onderbouwd en de verbanden met andere onderdelen zichtbaar?

## 5. Borg de specifieke VIVES-vereisten

Controleer onderstaande punten aan de hand van de aangeleverde bron. Voor de richtlijnen 2025–2026 moeten ze herkenbaar terugkomen:

- Organisatie, missie, visie, strategie, WHY en WHY NOW.
- Duidelijke probleemstelling, doelen en scope.
- Route to Value: capabilities → procesverandering → voordelen → KPI’s.
- Financiële businesscase of onderbouwde voordeelcase, met zichtbare aannames en onzekerheden.
- Drie relevante DAMA-topics, samen circa 400 woorden voor de deelopdracht.
- Circa zes KPI’s, benodigde databronnen, BI-tool en dashboardvisualisaties.
- Beschrijving en motivering van de AI-methodiek.
- Bij GenAI: aandacht voor informatiebetrouwbaarheid, procesinrichting en change management; niet automatisch een eigen trainingsdataset eisen.
- Strategie- en businessarchitectuur in ArchiMate 3.1.
- Businessanalyse in BPMN 2.0.
- Make-or-buy, benodigde capabilities, resources en migratiepad.
- Businessrequirements en minstens functionele requirements óf user stories.
- MoSCoW-prioritering.
- Motivation-laag, Decision-laag en niet-functionele requirements als optioneel volgens de bron.
- Relevante wetgeving, één uitgebreid besproken juridische uitdaging en een gemotiveerde beoordeling volgens de AI-verordening.
- Vier ethische stakeholders, waarvan minstens één daadwerkelijk geïnterviewd.
- Minstens twee ethische waarden, elk met handelingsopties voor technologie, omgeving en gebruiker.
- De voorgeschreven verkorte Trustworthy AI-zelfevaluatie. Een overzicht van zeven principes vervangt de vragenlijst niet.
- Reflectie op bestede tijd en zinvolheid van de juridische en ethische analyse.
- Inzichten uit de sociologische lessen en Sustainable AI in business.
- Een samenhangende synthese en onderbouwd advies.
- APA-bronvermelding en transparante vermelding van generatieve AI.
- Projectvoorstel van maximaal drie pagina’s.
- Eindcase van maximaal 20.000 woorden, inclusief titelpagina, samenvatting en bijlagen.
- Leesbare bijlagen in het einddocument; externe links vervangen deze niet.
- Verdediging met maximaal tien minuten presentatie en twintig minuten juryvragen.

Vul geen interviews, meetresultaten, juridische conclusies, goedkeuringen of gerealiseerde resultaten fictief in.

## 6. Maak verbanden zichtbaar

Gebruik consistente identificaties, bijvoorbeeld:

- `STR-01`: strategisch doel.
- `DOEL-01`: projectdoel.
- `ST-01`: stakeholder.
- `KPI-01`: meetpunt.
- `DATA-01`: databron.
- `BR-01`: businessrequirement.
- `FR-01`: functionele requirement.
- `NFR-01`: niet-functionele requirement.
- `RIS-01`: risico.
- `BRON-01`: bron.
- `BIJL-01`: bijlage.

Laat de tabellen verwijzen naar deze identificaties. Help de schrijver aantonen hoe probleem, strategie, oplossing, waarde, requirements, impact en advies samenhangen.

## 7. Controleer het aangemaakte resultaat

Voer na het schrijven een controle uit:

1. Controleer of alle geplande secties en pagina’s bestaan.
2. Vergelijk de werkelijke aantallen en titels met het ontwerp.
3. Controleer of paginatitels daadwerkelijk in OneNote zijn opgeslagen, niet alleen als kop in de pagina-inhoud.
4. Controleer steekproefsgewijs de tekst en tabellen.
5. Herstel ontbrekende of lege titels en onvolledige pagina’s.
6. Controleer de dekking van alle bronvereisten.
7. Respecteer eventuele wachttijden en verzoeklimieten van Microsoft.
8. Maak bij een onderbreking geen duplicaten; controleer eerst wat al is aangemaakt.

Meld alleen wat daadwerkelijk is uitgevoerd en gecontroleerd. Als een functie niet beschikbaar is, beschrijf concreet wat wel en niet is voltooid.

## 8. Lever het resultaat op

Geef een korte oplevering met:

- De naam van het nieuwe OneNote-notitieblok.
- Een rechtstreekse klikbare link.
- Het werkelijke aantal secties en pagina’s.
- Een korte beschrijving van de invulpagina’s.
- De pagina waarmee de gebruiker het beste begint.
- Eventuele ontbrekende aanvullende bronbestanden.

Vermeld dat dit een praktisch invulsjabloon op basis van de VIVES-richtlijnen is en dat de officiële VIVES-templates en actuele indieningsvoorwaarden afzonderlijk moeten worden gecontroleerd.

**Voer de volledige creatie en controle uit binnen de beschikbare mogelijkheden.**
```

## Verwachte uitvoer

- Een nieuw OneNote-notitieblok met alle bronvereisten verwerkt in secties en invulpagina’s.
- Een herkenbaar onderscheid tussen verplichte, optionele en aanbevolen onderdelen.
- Concrete schrijfvragen, tabellen en ruimte voor tekst, bronnen, aannames en vervolgacties.
- Een gecontroleerde structuur met correcte paginatitels.
- Een oplevering met de link, werkelijke aantallen en eventuele beperkingen.

## Oefening

1. Voeg het VIVES-pdf-document toe en controleer of de OneNote-koppeling beschikbaar is.
2. Kies een unieke notitiebloknaam en voer de volledige masterprompt uit.
3. Controleer de vereistenpagina en vergelijk steekproefsgewijs enkele invulpagina’s met de bron.
4. Bekijk het [bestaande OneNote-invulsjabloon en de gebruiksaanwijzing](../../templates/ai-use-case/).

## Aandachtspunten

- Het pdf-document is niet in dit promptbestand opgenomen; lever het afzonderlijk aan.
- Deze prompt maakt daadwerkelijk een nieuw notitieblok. Gebruik voor iedere uitvoering een passende naam.
- Het resultaat is een praktisch werksjabloon, geen officieel VIVES-documenttemplate.
- Deadlines en aanvullende VIVES-instructies moeten voor het toepasselijke academiejaar worden gecontroleerd.
- De prompt bevat geen opdracht om het aangemaakte notitieblok publiek te delen of te exporteren.
- Interviews, meetresultaten en juridische conclusies blijven invulbaar totdat ze werkelijk zijn onderbouwd.

## Wijzigingshistoriek

| Versie | Datum | Wijziging |
| --- | --- | --- |
| 1.0 | 2026-10-09 | Volledige masterprompt uit de chatsessie opgeslagen, met metadata en gebruiksinstructies |
