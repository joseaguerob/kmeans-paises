# K-Means: agrupación de países

Caso de clustering con K-Means (aprendizaje no supervisado). Se agrupan 167 países según mortalidad infantil (`child_mort`) y PIB per cápita (`gdpp`).

## Dataset
- Kaggle: https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data
- Copia del CSV en `data/country_data.csv`: https://github.com/AhmetZamanis/ClusteringCountry/blob/main/country_data.csv

## Contenido
- `02_KMeans_Paises.ipynb`: K-Means con sklearn, K-Means paso a paso, inercia y método del codo, interpretación.
- `data/`: dataset.
- `imagenes/`: gráficos generados.

## Ejecución
```bash
pip install -r requirements.txt
jupyter notebook 02_KMeans_Paises.ipynb
```

## Resultado
K = 3 (método del codo y silueta 0.589): alto desarrollo (30 países), desarrollo medio (93) y prioridad de ayuda (44).
