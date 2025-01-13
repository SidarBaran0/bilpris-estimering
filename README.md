# Bilpris Estimering

Dette prosjektet estimerer priser på biler basert på ulike egenskaper som produksjonsår, kilometerstand, drivstofftype, og girtype. Prosjektet bruker maskinlæringsmodellen Gradient Boosting for å forutsi priser med høy nøyaktighet.

## Teknologier
- **Programmeringsspråk**: Python
- **Biblioteker**: 
  - `pandas`, `numpy`, `seaborn`, `matplotlib` for dataanalyse og visualisering.
  - `scikit-learn` for maskinlæring.

## Funksjoner
- Dataforberedelse: Fjerner manglende verdier og konverterer kategoriske variabler til numeriske ved hjelp av One-Hot Encoding.
- Modelltrening: Gradient Boosting-modellen brukes til å trene på dataene og evaluere prediksjonsnøyaktigheten.
- Visualiseringer: 
  - Histogram for prisfordeling.
  - Korrelasjonskart for å vise sammenhenger mellom variabler.
  - Scatterplot som viser sammenheng mellom produksjonsår og pris.
- Prisestimering: Eksempeldata brukes til å forutsi prisen på en bil.

## Hvordan kjøre koden
1. Sørg for at du har installert nødvendige Python-biblioteker:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
