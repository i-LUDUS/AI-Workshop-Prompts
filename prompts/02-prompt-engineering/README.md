# Prompt engineering

Deze categorie bevat **16 Nederlandstalige voorbeeldprompts** voor de AI-workshops van i-LUDUS. Iedere techniek heeft een eigen Markdown-bestand (versie **1.1**) dat is uitgewerkt volgens het [standaard prompt-template](../../templates/prompt-template.md), met metadata, doel, gebruiksmoment, invoerparameters, een kopieerbare prompt, verwachte uitvoer, oefening, aandachtspunten en wijzigingshistoriek.

## Snel starten

1. Kies hieronder een techniek en open het bijbehorende Markdown-bestand.
2. Lees het doel en de eventuele invoerparameters.
3. Kopieer de inhoud van het codeblok onder **Prompt** en vervang placeholders zoals `{{usecase}}` door fictieve of toegestane gegevens.
4. Voer de prompt uit in een geschikte AI-toepassing en vergelijk de resultaten via de voorgestelde oefening.
5. Controleer de uitkomst op juistheid, volledigheid en bronbetrouwbaarheid.

## Overzicht van de 16 technieken

| Nr. | Promptingtechniek | Wat leer je? | Open prompt |
| ---: | --- | --- | --- |
| 1 | Zero-shot | Een opdracht uitvoeren zonder voorbeelden | [Open bestand](01-zero-shot.md) |
| 2 | One-shot | Eén voorbeeld gebruiken om het gewenste antwoord te tonen | [Open bestand](02-one-shot.md) |
| 3 | Few-shot | Meerdere voorbeelden gebruiken om een patroon duidelijk te maken | [Open bestand](03-few-shot.md) |
| 4 | Rolprompt | Een expertrol instellen voor de AI-assistent | [Open bestand](04-rolprompt.md) |
| 5 | Contextprompt | Relevante achtergrondinformatie toevoegen | [Open bestand](05-contextprompt.md) |
| 6 | Gestructureerde prompt | Een vaste antwoordstructuur opleggen | [Open bestand](06-gestructureerde-prompt.md) |
| 7 | Stapsgewijze prompt | Een opdracht opdelen in zichtbare beoordelingsstappen | [Open bestand](07-stapsgewijze-prompt.md) |
| 8 | Decompositie | Een complex probleem opdelen in deelopdrachten | [Open bestand](08-decompositie.md) |
| 9 | Constraints | Beperkingen instellen, zoals lengte of aantal aanbevelingen | [Open bestand](09-constraints.md) |
| 10 | Outputformaat | Een specifiek resultaatformaat voorschrijven | [Open bestand](10-outputformaat.md) |
| 11 | RAG / brongebaseerd | Antwoorden laten onderbouwen met beschikbare documenten | [Open bestand](11-rag-brongebaseerd.md) |
| 12 | Zelfkritiek | Een voorstel kritisch beoordelen en verbeteren | [Open bestand](12-zelfkritiek.md) |
| 13 | Evaluatie | Een oplossing beoordelen volgens vooraf bepaalde criteria | [Open bestand](13-evaluatie.md) |
| 14 | Tool use | Een AI-assistent beschikbare analysetools laten inzetten | [Open bestand](14-tool-use.md) |
| 15 | Persona en doelgroep | Een antwoord afstemmen op rol en doelpubliek | [Open bestand](15-persona-en-doelgroep.md) |
| 16 | Masterprompt | Verschillende instructies combineren in een herbruikbare prompt | [Open bestand](16-masterprompt.md) |

## Voorgesteld leertraject

### 1. Basis

- [Zero-shot](01-zero-shot.md) — een opdracht uitvoeren zonder voorbeelden.
- [One-shot](02-one-shot.md) — eén voorbeeld gebruiken om het gewenste antwoord te tonen.
- [Few-shot](03-few-shot.md) — meerdere voorbeelden gebruiken om een patroon duidelijk te maken.

### 2. Instructies en context

- [Rolprompt](04-rolprompt.md) — een expertrol instellen voor de ai-assistent.
- [Contextprompt](05-contextprompt.md) — relevante achtergrondinformatie toevoegen.
- [Gestructureerde prompt](06-gestructureerde-prompt.md) — een vaste antwoordstructuur opleggen.
- [Constraints](09-constraints.md) — beperkingen instellen, zoals lengte of aantal aanbevelingen.
- [Outputformaat](10-outputformaat.md) — een specifiek resultaatformaat voorschrijven.
- [Persona en doelgroep](15-persona-en-doelgroep.md) — een antwoord afstemmen op rol en doelpubliek.

### 3. Probleemoplossing

- [Stapsgewijze prompt](07-stapsgewijze-prompt.md) — een opdracht opdelen in zichtbare beoordelingsstappen.
- [Decompositie](08-decompositie.md) — een complex probleem opdelen in deelopdrachten.

### 4. Bronnen en tools

- [RAG / brongebaseerd](11-rag-brongebaseerd.md) — antwoorden laten onderbouwen met beschikbare documenten.
- [Tool use](14-tool-use.md) — een ai-assistent beschikbare analysetools laten inzetten.

### 5. Kwaliteitscontrole

- [Zelfkritiek](12-zelfkritiek.md) — een voorstel kritisch beoordelen en verbeteren.
- [Evaluatie](13-evaluatie.md) — een oplossing beoordelen volgens vooraf bepaalde criteria.

### 6. Integratie

- [Masterprompt](16-masterprompt.md) — verschillende instructies combineren in een herbruikbare prompt.

## Didactische aandachtspunten

- **Vergelijk technieken:** voer dezelfde of een vergelijkbare opdracht uit met en zonder voorbeelden, context, structuur of beperkingen.
- **Werk veilig:** gebruik fictieve voorbeelden en deel geen persoonsgegevens, bedrijfsgeheimen of API-sleutels zonder passende waarborgen.
- **Controleer antwoorden:** AI kan overtuigend klinkende fouten maken; valideer feiten, berekeningen en bronverwijzingen.
- **Weet wat je test:** een prompt die documenten noemt is op zichzelf nog geen volledig RAG-systeem; toolgebruik vereist een AI-platform met de nodige rechten en beschikbare functies.
- **Combineer technieken:** de technieken sluiten elkaar niet uit; de masterprompt toont hoe je meerdere patronen samenbrengt.

## Zelf een prompt toevoegen

Gebruik het [prompt-template](../../templates/prompt-template.md) voor nieuwe bijdragen. Documenteer minstens de metadata, de invoerparameters, het codeblok met de prompt, de verwachte uitvoer, een oefening en de wijzigingshistoriek. Houd de prompttaal en de uitvoertaal expliciet bij.

Terug naar het [hoofdoverzicht van de promptbibliotheek](../../README.md).
