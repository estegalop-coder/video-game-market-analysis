# Análisis del mercado de videojuegos

## Descripción del proyecto

Este proyecto analiza datos históricos de videojuegos para identificar patrones de lanzamiento, ventas, plataformas, géneros y diferencias entre regiones. El análisis utiliza datos disponibles hasta 2016 y considera que los registros de ese año podrían estar incompletos.

## Objetivo

Identificar patrones de ventas y comportamiento del mercado que ayuden a reconocer plataformas y géneros relevantes, así como diferencias entre Norteamérica, Europa y Japón.

## Datos

El conjunto `games.csv` contiene información sobre videojuegos, incluyendo:

- Nombre, plataforma, género y año de lanzamiento.
- Ventas en Norteamérica, Europa, Japón y otras regiones.
- Puntuaciones de críticos y usuarios.
- Clasificación ESRB.

El archivo de datos se encuentra en `datos/games.csv`.

## Herramientas

- Python
- pandas y NumPy para preparación y análisis de datos.
- Matplotlib y Seaborn para visualizaciones.
- SciPy para pruebas estadísticas, si se utiliza en el notebook.
- Jupyter Notebook.

## Estructura del proyecto

```text
video-game-market-analysis/
├── datos/
│   └── games.csv
├── notebooks/
│   └── video_game_market_analysis.ipynb
├── resultados/
│   ├── distribucion_ventas_plataforma.png
│   ├── evolucion_ventas_plataformas.png
│   ├── resenas_y_ventas_ps4.png
│   ├── ventas_mismos_juegos_plataforma.png
│   ├── ventas_plataformas_populares.png
│   ├── ventas_por_genero.png
│   └── videojuegos_por_anio.png
└── README.md
```

## Etapas del análisis

1. Revisión y preparación de los datos.
2. Análisis de lanzamientos y evolución de plataformas.
3. Análisis de ventas por plataforma y género.
4. Relación entre puntuaciones de críticos, usuarios y ventas.
5. Comparación de perfiles regionales: Norteamérica, Europa y Japón.
6. Pruebas de hipótesis estadísticas.
7. Conclusiones y recomendaciones basadas en los resultados.

## Cómo ejecutar el proyecto

1. Clona o descarga el repositorio.
2. Instala las dependencias:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

3. Abre `notebooks/video_game_market_analysis.ipynb` en VS Code o Jupyter.
4. Ejecuta las celdas en orden. El notebook espera encontrar el CSV en `datos/games.csv` y guarda las gráficas exportadas en `resultados/`.

## Consideraciones y limitaciones

- Los registros de 2016 podrían estar incompletos.
- Las ventas históricas no garantizan resultados futuros ni permiten afirmar rentabilidad sin considerar costos.
- Los valores ausentes y las limitaciones del conjunto de datos deben tenerse en cuenta al interpretar los resultados.

## Contexto

Proyecto académico desarrollado como parte de la formación en análisis de datos de TripleTen y adaptado para un portafolio profesional.
