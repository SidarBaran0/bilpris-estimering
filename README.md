Dette prosjektet estimerer priser på biler basert på ulike egenskaper som produksjonsår, kjørelengde, drivstofftype og girtype. Prosjektet benytter ensemble-metoder, inkludert Stacking, for å oppnå høy presisjon i prediksjonene.

Teknologier
Programmeringsspråk: Python
Biblioteker:
pandas, numpy, seaborn, matplotlib for dataanalyse og visualisering.
scikit-learn for maskinlæring.
Funksjoner
Dataforberedelse:
Fjerner manglende verdier.
Konverterer kategoriske variabler til numeriske med One-Hot Encoding.
Skalerer numeriske variabler med StandardScaler.
Modelltrening:
Gradient Boosting og Random Forest brukes som base-modeller.
Stacking-modellen kombinerer disse to modellene med en Linear Regression som meta-learner for å forbedre prediksjonsnøyaktigheten.
Visualiseringer:
Histogram for prisfordeling.
Korrelasjonskart for å vise sammenhenger mellom variabler.
Scatterplot som viser forholdet mellom produksjonsår og pris.
Prisestimering:
Eksempeldata brukes til å forutsi prisen på en bil ved hjelp av den mest presise modellen (Stacking).
