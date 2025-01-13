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

## Resultater
- Modellen oppnår en R²-score på 0.94, noe som indikerer høy nøyaktighet i prediksjonene.
- Diagrammer gir visuell innsikt i datafordeling og sammenhenger mellom variabler.
