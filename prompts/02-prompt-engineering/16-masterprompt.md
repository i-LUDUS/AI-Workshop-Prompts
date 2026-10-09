# Masterprompt

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Masterprompt |
| Categorie | 02 – Prompt engineering |
| Versie | 1.2 |
| Status | workshopklaar |
| Prompttaal | nl, en |
| Uitvoertaal | nl, en |
| AI-platform | Platformonafhankelijk |

## Doel

De deelnemer leert de techniek masterprompt herkennen en toepassen in een concrete zakelijke AI-opdracht.

## Wanneer gebruiken?

Gebruik deze techniek om gerichter te sturen op de kwaliteit, bruikbaarheid en controleerbaarheid van AI-antwoorden. De precieze mogelijkheden verschillen per platform.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{usecase}}` | Ja | Vul usecase in met relevante, fictieve gegevens | Dossierclassificatie |

## Prompt (Nederlands)

Kopieer onderstaande prompt en vervang eventuele placeholders.

```text
Je bent AI-businessanalist. Analyseer de volgende use-case: {{usecase}}. Beschrijf probleem, doel, stakeholders, benodigde data, mogelijke AI-aanpak, verwachte baten, kosten, risico's en KPI's. Scheid feiten van aannames, verzin geen cijfers en geef ontbrekende informatie expliciet aan. Presenteer het resultaat in vaste rubrieken en sluit af met een onderbouwde go/no-go-aanbeveling.
```

## Prompt (English)

Copy the prompt below and replace placeholders with the same input values as in the Dutch version.

```text
You are an AI business analyst. Analyze the following use case: {{usecase}}. Describe the problem, objective, stakeholders, required data, possible AI approach, expected benefits, costs, risks and KPIs. Separate facts from assumptions, do not invent figures and explicitly identify missing information. Present the result under fixed headings and end with a well-supported go/no-go recommendation.
```

## Verwachte uitvoer

Een gestructureerd en relevant antwoord dat de opgegeven instructies volgt. Controleer of het antwoord de opdracht volledig uitvoert en eventuele onzekerheden vermeldt.

## Oefening

1. Voer de prompt uit met fictieve voorbeeldgegevens of een testbestand.
2. Wijzig één invoergegeven of instructie en vergelijk de resultaten.
3. Bespreek de verschillen, beperkingen en mogelijke verbeteringen.

## Aandachtspunten

- Gebruik geen persoonsgegevens of vertrouwelijke bedrijfsinformatie zonder passende bescherming.
- Controleer belangrijke feiten, berekeningen en bronnen.
- Resultaten kunnen per model en uitvoering verschillen.

## Wijzigingshistoriek

| Versie | Datum | Wijziging |
| --- | --- | --- |
| 1.0 | 2026-10-09 | Eerste workshopvoorbeeld |
| 1.1 | 2026-10-09 | Conform template gestructureerd en didactisch aangevuld; prompt ongewijzigd |
| 1.2 | 2026-10-09 | Engelse prompt toegevoegd; Nederlandse prompt behouden |
