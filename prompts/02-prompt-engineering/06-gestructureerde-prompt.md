# Gestructureerde prompt

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Gestructureerde prompt |
| Categorie | 02 – Prompt engineering |
| Versie | 1.2 |
| Status | workshopklaar |
| Prompttaal | nl, en |
| Uitvoertaal | nl, en |
| AI-platform | Platformonafhankelijk |

## Doel

De antwoordstructuur vooraf bepalen. De deelnemer leert herkennen hoe deze techniek de kwaliteit, voorspelbaarheid of bruikbaarheid van AI-antwoorden beïnvloedt.

## Wanneer gebruiken?

Gebruik deze techniek wanneer je de antwoordstructuur vooraf bepalen. Het resultaat blijft afhankelijk van de beschikbare modelmogelijkheden, de invoer en de kwaliteit van de instructies.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{usecase}}` | Ja | Invoer voor usecase | Automatische dossierclassificatie |

## Prompt (Nederlands)

Kopieer de tekst in dit codeblok en vervang eventuele placeholders.

```text
Analyseer de volgende AI-use-case: {{usecase}}. Gebruik exact deze structuur: 1. Probleem, 2. Doel, 3. Stakeholders, 4. Data, 5. Technologie, 6. Risico's, 7. KPI's, 8. Aanbeveling.
```

## Prompt (English)

Copy the prompt below and replace placeholders with the same input values as in the Dutch version.

```text
Analyze the following AI use case: {{usecase}}. Use exactly this structure: 1. Problem, 2. Objective, 3. Stakeholders, 4. Data, 5. Technology, 6. Risks, 7. KPIs, 8. Recommendation.
```

## Verwachte uitvoer

Een antwoord dat de instructie volgt en de gekozen techniek herkenbaar toepast. Succescriteria: inhoudelijke relevantie, correcte interpretatie van de invoer, naleving van het gevraagde formaat en expliciete vermelding van onzekerheden waar nodig.

## Oefening

1. Vul eventuele parameters in met fictieve gegevens en voer de prompt uit.
2. Laat één rubriek weg en vergelijk de volledigheid.
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

| 1.2 | 2026-10-09 | Engelse prompt toegevoegd, Nederlandse versie behouden |
