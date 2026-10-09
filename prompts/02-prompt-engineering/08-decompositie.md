# Decompositie

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Decompositie |
| Categorie | 02 – Prompt engineering |
| Versie | 1.2 |
| Status | workshopklaar |
| Prompttaal | nl, en |
| Uitvoertaal | nl, en |
| AI-platform | Platformonafhankelijk |

## Doel

Een complex probleem in deelopdrachten splitsen. De deelnemer leert herkennen hoe deze techniek de kwaliteit, voorspelbaarheid of bruikbaarheid van AI-antwoorden beïnvloedt.

## Wanneer gebruiken?

Gebruik deze techniek wanneer je een complex probleem in deelopdrachten splitsen. Het resultaat blijft afhankelijk van de beschikbare modelmogelijkheden, de invoer en de kwaliteit van de instructies.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{proces}}` | Ja | Invoer voor proces | Afhandeling van inkomende e-mails |

## Prompt (Nederlands)

Kopieer de tekst in dit codeblok en vervang eventuele placeholders.

```text
Onderzoek dit proces: {{proces}}. Fase 1: beschrijf de huidige werking. Fase 2: identificeer knelpunten. Fase 3: stel AI-oplossingen voor. Geef daarna een prioriteitenlijst met motivatie.
```

## Prompt (English)

Copy the prompt below and replace placeholders with the same input values as in the Dutch version.

```text
Examine this process: {{proces}}. Phase 1: describe how it currently works. Phase 2: identify bottlenecks. Phase 3: propose AI solutions. Then provide a prioritized list with reasons.
```

## Verwachte uitvoer

Een antwoord dat de instructie volgt en de gekozen techniek herkenbaar toepast. Succescriteria: inhoudelijke relevantie, correcte interpretatie van de invoer, naleving van het gevraagde formaat en expliciete vermelding van onzekerheden waar nodig.

## Oefening

1. Vul eventuele parameters in met fictieve gegevens en voer de prompt uit.
2. Wijzig de volgorde van de fasen en vergelijk.
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
| 1.2 | 2026-10-09 | Engelse prompt toegevoegd; Nederlandse prompt behouden |
