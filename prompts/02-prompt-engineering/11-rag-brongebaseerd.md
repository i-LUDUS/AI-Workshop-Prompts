# RAG / brongebaseerd

## Metadata

| Veld | Waarde |
| --- | --- |
| Naam | RAG / brongebaseerd |
| Categorie | 02 – Prompt engineering |
| Versie | 1.2 |
| Status | workshopklaar |
| Prompttaal | nl, en |
| Uitvoertaal | nl, en |
| AI-platform | Platformonafhankelijk |

## Doel

De deelnemer leert de techniek rag / brongebaseerd herkennen en toepassen in een concrete zakelijke AI-opdracht.

## Wanneer gebruiken?

Gebruik deze techniek om gerichter te sturen op de kwaliteit, bruikbaarheid en controleerbaarheid van AI-antwoorden. De precieze mogelijkheden verschillen per platform.

## Invoerparameters

| Parameter | Verplicht? | Uitleg | Voorbeeld |
| --- | --- | --- | --- |
| `{{vraag}}` | Ja | Vul vraag in met relevante, fictieve gegevens | Wat is het beleid? |
| `{{documenten}}` | Ja | Vul documenten in met relevante, fictieve gegevens | Beleidsdocument A |

## Prompt (Nederlands)

Kopieer onderstaande prompt en vervang eventuele placeholders.

```text
Beantwoord de vraag '{{vraag}}' uitsluitend op basis van de volgende documenten: {{documenten}}. Vermeld per belangrijke bewering de documentnaam en vindplaats. Als de informatie ontbreekt, antwoord dan 'Niet gevonden in de aangeleverde documenten'. Verzin geen bronnen.
```

## Prompt (English)

Copy the prompt below and replace placeholders with the same input values as in the Dutch version.

```text
Answer the question '{{vraag}}' using only the following documents: {{documenten}}. For each important claim, cite the document name and the relevant location within that document. If the information is missing, respond 'Not found in the supplied documents'. Do not invent sources.
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
- Een brongebaseerde prompt alleen is nog geen volledige RAG-architectuur; daarvoor is documentophaling nodig.

## Wijzigingshistoriek

| Versie | Datum | Wijziging |
| --- | --- | --- |
| 1.0 | 2026-10-09 | Eerste workshopvoorbeeld |
| 1.1 | 2026-10-09 | Conform template gestructureerd en didactisch aangevuld; prompt ongewijzigd |
| 1.2 | 2026-10-09 | Engelse prompt toegevoegd; Nederlandse prompt behouden |
