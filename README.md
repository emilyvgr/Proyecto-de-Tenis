# ¿Influye significativamente la superficie de la cancha en la probabilidad de que gane el jugador mejor rankeado (o favorito según odds)?
El problema central de este estudio radica en lo infravalorada que esta la superficie como predictor de rendimiento. Para abordar esta problematica, se dispone de un conjunto de datos historicos que abarcan desde el año 2000 hasta el año 2026, el cual incluye palmares, marcadores detallados y determinacion del jugdor favorito previo al encuentro. La existencia de estos datos permite identificar el sesgo sistematico: mientras que las cuotas de apuestasy el favoritismo suelen seguir la inercia del ranking ATP/WTA, el analisis historicos de los marcadores revela que la superficie actua como un ecualizador que invalida las jerarquias tradicionales. El problema, por lo tanto, es la ausencia de un modelo integral que use estos 26 años de historia para corregir las predicciones basadas puramente en el nombre del jugador, optimizando asi la toma de decisiones en el mercado deportivo.

## Objetivo general.
Analizar el impacto de la superficie de la cancha (hard, clay, grass) en la probabilidad de que el jugador favorito (determinado por ranking ATP o cuotas de apuestas) gane un partido de tenis profesional, utilizando técnicas estadísticas descriptivas e inferenciales en una base de datos de aproximadamente 6.000 partidos.

## Objetivos especificos.
  1. Caracterizar la distribución de partidos por superficie de cancha, ronda del torneo y nivel del evento (Series), identificando patrones descriptivos en la base de datos.
  2. Calcular y comparar la proporción de victorias del jugador favorito (definido como el de mejor ranking o menor odd) en cada tipo de superficie (hard, clay, grass).
  3. Evaluar si existe una asociación estadísticamente significativa entre la superficie de la cancha y la victoria del favorito, mediante pruebas de hipótesis (como chi-cuadrado de independencia).
  4. Modelar la probabilidad de victoria del favorito en función de la superficie y otras covariables relevantes (como diferencia de ranking, ronda o best-of sets) utilizando regresión logística.
  5. Generar visualizaciones interactivas y estáticas que faciliten la interpretación de los resultados, para su inclusión en un reporte PDF y un dashboard en R.
  6. Interpretar los hallazgos en el contexto del tenis profesional y discutir implicaciones prácticas (por ejemplo, en predicción de resultados o estrategias de juego).




