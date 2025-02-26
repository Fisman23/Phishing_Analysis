# Análisis de URLs de Phishing
Este proyecto analiza un dataset de URLs para identificar patrones que diferencien sitios de phishing de sitios legítimos.

## Contenido
- `data/`: Dataset original (`phishing_site_urls.csv`).
- `resultados/`: Gráficas generadas (longitud de URLs y palabras comunes).
- `analisis_phishing.py`: Script en Python para el análisis.

## Requisitos
- Python 3.x
- Bibliotecas: pandas, matplotlib, seaborn, scikit-learn

## Ejecución
1. Coloca el archivo `phishing_site_urls.csv` en la carpeta `data/`.
2. Ejecuta: `python analisis_phishing.py`.

## Resultados
- Distribución de la longitud de URLs según su clasificación.
- Top 10 palabras más comunes en URLs de phishing.
