# Stapsgewijze prompt

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | Stapsgewijze prompt |
| Categorie | 02 – Prompt engineering |
| Versie | 1.1 |
| Status | workshopklaar |
| Prompttaal | nl |
| Uitvoertaal | nl |
| AI-platform | Platformonafhankelijk |

## Doel

Een opdracht in opeenvolgende stappen opdelen. De deelnemer leert herkennen hoe deze techniek de kwaliteit, voorspelbaarheid of bruikbaarheid van AI-antwoorden beïnvloedt.

## Wanneer gebruiken?

Gebruik deze techniek wanneer je een opdracht in opeenvolgende stappen opdelen. Het resultaat blijft afhankelijk van de beschikbare modelmogelijkheden, de invoer en de kwaliteit van de instructies.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{proces}}` | Ja | Invoer voor proces | Afhandeling van inkomende e-mails |

## Prompt

Kopieer de tekst in dit codeblok en vervang eventuele placeholders.

```text
Beoordeel het proces {{proces}} op automatiseringspotentieel. Geef achtereenvolgens criteria, beoordeling, risico's en conclusie, telkens met een korte toelichting.
```

## Verwachte uitvoer

Een antwoord dat de instructie volgt en de gekozen techniek herkenbaar toepast. Succescriteria: inhoudelijke relevantie, correcte interpretatie van de invoer, naleving van het gevraagde formaat en expliciete vermelding van onzekerheden waar nodig.

## Oefening

1. Vul eventuele parameters in met fictieve gegevens en voer de prompt uit.
2. Vergelijk met een prompt die enkel een conclusie vraagt.
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
