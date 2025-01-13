# Bilpris Estimering

Dette prosjektet estimerer priser på biler basert på ulike egenskaper som produksjonsår, kjørelengde, drivstofftype og girtype. Prosjektet benytter ensemble-metoder, inkludert Stacking, for å oppnå høy presisjon i prediksjonene.

## Teknologier

- **Programmeringsspråk:** Python
- **Biblioteker:**
  - `pandas`, `numpy`, `seaborn`, `matplotlib` for dataanalyse og visualisering.
  - `scikit-learn` for maskinlæring.

## Funksjoner

- **Dataforberedelse:**
  - Fjerner manglende verdier.
  - Konverterer kategoriske variabler til numeriske med One-Hot Encoding.
  - Skalerer numeriske variabler med StandardScaler.
- **Modelltrening:**
  - Gradient Boosting og Random Forest brukes som base-modeller.
  - Stacking-modellen kombinerer disse to modellene med en Linear Regression som meta-learner for å forbedre prediksjonsnøyaktigheten.
- **Visualiseringer:**
  - Histogram for prisfordeling.
  - Korrelasjonskart for å vise sammenhenger mellom variabler.
  - Scatterplot som viser forholdet mellom produksjonsår og pris.
- **Prisestimering:**
  - Eksempeldata brukes til å forutsi prisen på en bil ved hjelp av den mest presise modellen (Stacking).

## Ensemble-metoder og Stacking

Prosjektet bruker ensemble-metoder for å forbedre nøyaktigheten. Spesielt kombineres Gradient Boosting og Random Forest ved hjelp av en StackingRegressor. Dette gir en samlet modell som utnytter styrkene til begge base-modellene, og forbedrer ytelsen ved å bruke en Linear Regression som meta-learner.

**Resultater fra modellene:**
- **Gradient Boosting:**
  - Gjennomsnittlig R²-score: 0.92
- **Random Forest:**
  - Gjennomsnittlig R²-score: 0.78
- **Stacking-modell:**
  - Gjennomsnittlig R²-score: 0.93 (med lav standardavvik, som indikerer stabilitet).
