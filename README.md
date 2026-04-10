# Analitica-Predictiva-Subasta-Ganadera

Proyecto de Analítica Predictiva Aplicada a los Negocios
INTEP Roldanillo Valle | Postgrado Especialización en Big Data y Analítica de Datos| 2026

## Equipo
- Carlos Arturo Agudelo
- Jefferson Balcazar Gomez
- Milton Vanegas Delgado

## Descripción
Las ventas del ganado en aproximadamente un 90% de los casos se realizan subastando el kilo de cada Lote, es por ello que decidimos enfocar la analitica predictiva de dichos precios, tomando como referencia aproximadamente 9 meses de datos de las ventas, contando con datos relevantes como el peso, la categoria(sexo), la procedencia

## Archivos
- `Analitica_Predictiva_Subasta_Ganadera_Presentacion.ipynb` — Código Python completo
- `Analitica_Predictiva_Subasta_Ganadera_Presentacion.pptx` — Diapositivas de la exposición
- `Analitica_Predictiva_Subasta_Ganadera_Presentacion.pdf` — Informe ejecutivo para el gerente
- `Analitica_Predictiva_Subasta_Ganadera_Presentacion.csv` — Dataset

## Modelos usados
- Regresion lineal (Simple y Multiplpe)
- Series Temporales (Holt-Wimters)
- Arbol de desicion
- K-Means (Clustering)

## Resultado Principal
En base a los resultados y metricas, podemos decir que el comportamiento del precio no es tan facil de explicar con las pocas variables que tenemos , la gran mayoria (70%), son variables independientes que no tenemos en el momento.

Los perfiles comerciales ha sido nuestro principal hallazgo, no se ven a simple vista pero gracias al modelo K-Means logramos identificarlos y crear campañas de Marketing dirigidas a ellos

## Tecnologias
Python, Pandas, glob, seaborn, matplotlib, sklearn, numpy, statsmodels.tsa.holtwinters
