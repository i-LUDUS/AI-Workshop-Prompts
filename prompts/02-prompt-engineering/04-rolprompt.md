# Rolprompt

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Rolprompt |
| Categorie | 02 – Prompt engineering |
| Versie | 1.2 |
| Status | workshopklaar |
| Prompttaal | nl, en |
| Uitvoertaal | nl, en (volgens promptversie) |
| AI-platform | Platformonafhankelijk |

## Doel

Een expertise-rol meegeven. De deelnemer leert herkennen hoe deze techniek de kwaliteit, voorspelbaarheid of bruikbaarheid van AI-antwoorden beïnvloedt.

## Wanneer gebruiken?

Gebruik deze techniek wanneer je een expertise-rol meegeven. Het resultaat blijft afhankelijk van de beschikbare modelmogelijkheden, de invoer en de kwaliteit van de instructies.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{procesbeschrijving}}` | Ja | Invoer voor procesbeschrijving | Afhandeling van inkomende e-mails |

## Prompt (Nederlands)

Kopieer de tekst in dit codeblok en vervang eventuele placeholders.

```text
Je bent een ervaren Lean Six Sigma Black Belt. Analyseer het volgende proces en benoem de belangrijkste vormen van verspilling: {{procesbeschrijving}}.
```

## Prompt (English)

Copy the text below and replace any placeholders with the same input values used in the Dutch version.

```text
You are an experienced Lean Six Sigma Black Belt. Analyze the following process and identify the main forms of waste: {{procesbeschrijving}}.
```

## Verwachte uitvoer

Een antwoord dat de instructie volgt en de gekozen techniek herkenbaar toepast. Succescriteria: inhoudelijke relevantie, correcte interpretatie van de invoer, naleving van het gevraagde formaat en expliciete vermelding van onzekerheden waar nodig.

## Oefening

1. Vul eventuele parameters in met fictieve gegevens en voer de prompt uit.
2. Vergelijk het antwoord met dezelfde vraag zonder rol.
3. Beoordeel het resultaat op juistheid, duidelijkheid en volledigheid; bespreek mogelijke verbeteringen.

## Aandachtspunten

- Deel geen vertrouwelijke of persoonlijke informatie.
- Controleer belangrijke feiten en bronnen; AI-antwoorden kunnen fouten bevatten.
- Resultaten kunnen verschillen per AI-model en uitvoering.

## Wijzigingshistoriek

| Versie | Datum | Wijziging |
| --- | --- | --- |
| 1.0 | 2026-10-09 | Eerste workshopvoorbeeld |
| 1.1 | 2026-10-09 | Gestandaardiseerd volgens officiële prompt-template; didactische rubrieken toegevoegd; oorspronkelijke prompt behouden |
| 1.2 | 2026-10-09 | Engelse promptvertaling toegevoegd; Nederlandse prompt en placeholders behouden |
