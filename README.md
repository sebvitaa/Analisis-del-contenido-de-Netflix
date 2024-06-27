# Proyecto: Análisis de Películas en Netflix (2008-2021)

## Resumen

Este proyecto se desarrolla en el marco del curso **Taller de Visualización de la Información**. Su objetivo es realizar un análisis exhaustivo de las películas que han sido subidas a la plataforma de streaming Netflix desde el año 2008 hasta el 2021. Para presentar los datos que surjan del análisis, es esencial utilizar las técnicas de visualización de la información aprendidas en el curso. Estas técnicas, no solo nos permitirán presentar los datos de forma clara, sino que facilitarán la identificación de tendencias y patrones dentro del conjunto de datos analizado.

En este proyecto, los colaboradores fueron Renato Fernández, Valentina Jiménez, Sebastián Ramírez y Vicente Ramírez. Con la supervisión y ayuda de la docente guía Daniela Opitz.

Se utilizó únicamente dataset llamado Netflix Movies and TV Shows - EDA

## Objetivo del Proyecto

El principal objetivo de este proyecto es identificar y analizar los tipos de películas que han sido más subidas a Netflix durante el período mencionado. A partir de este análisis, se busca:

1. **Objetivo 1**: Identificar patrones y tendencias de producción de películas en diferentes zonas geográficas. 

2. **Objetivo 2**: Analizar la evolución del catálogo y evaluar la diversidad en el contenido de Netflix.

## Contenidos del Proyecto

El proyecto incluye los siguientes componentes:

- **Recopilación de Datos**: Recolección de datos sobre las películas disponibles en Netflix desde 2008 hasta 2021.
- **Limpieza de Datos**: Procesamiento y depuración de los datos recolectados para asegurar su calidad y fiabilidad.
- **Visualización de Resultados**: Creación de gráficos y visualizaciones para presentar los hallazgos de manera clara y comprensible.
- **Conclusiones**: Interpretación de los resultados obtenidos y discusión sobre las implicaciones del análisis tanto para la producción como para el consumo de material audiovisual en Netflix.

## Herramientas y Tecnologías

El proyecto utiliza una variedad de herramientas y tecnologías, incluyendo:

- **Python**: Para la manipulación y análisis de datos.
- **Pandas**: Para la limpieza y análisis de datos.
- **Matplotlib y Seaborn**: Para la creación de visualizaciones estáticas.
- **Jupyter Notebooks**: Para documentar el proceso de análisis y las visualizaciones.

## Visualizaciones obtenidas

- **Películas vs series**: Para determinar cuantas películas y series hay en el dataset.
![CantPeliculaSerie](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/CantPeliculaSerie.jpg)

- **Top Categorías**: Para determinar las categorías más repetidas.
![top_categorías](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/top_categor%C3%ADas.jpg)

- **Top Países**: Para determinar los países más repetidos.
![top_paises](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/top_paises.jpg)

- **Top Países Storyline**: Para determinar los países más repetidos como evolución del tiempo.
![top_paises_storyline](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/top_paises_storyline.jpg)
![top_paises_acumulado_storyline](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/top_paises_acumulado_storyline.jpg)

- **Proveniencia top 3**: Para determinar de donde vienen las películas de las categorías más vistas.
![Proveniencia_peliculas_drama](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/Proveniencia_peliculas_drama.jpg)
![Proveniencia_peliculas_internacionales](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/Proveniencia_peliculas_internacionales.jpg)
![Proveniencia_peliculas_comedia](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/Proveniencia_peliculas_comedia.jpg)

- **Entropía**: Para determinar la variación de las categorías en función del tiempo.
![Entropia](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/Entropia.jpg)

- **Películas por año**: Mapa de calor acerca de las películas y su categoría por año
![hm_genre_per_year](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/blob/main/Netflix/hm_genre_per_year.jpg)

## Conclusión

Este proyecto proporciona una visión detallada sobre las tendencias de producción y consumo de películas en Netflix desde 2008 hasta 2021. A través del análisis y la visualización de datos, se puede entender mejor qué tipo de contenido domina la plataforma y cómo esto puede ayudar a los productores y directores a elegir que tipo de contenido producir.

## Referencias

Los siguientes enlaces dirigen a los archivos de los cuales estan basados los códigos de este análisis
- 	[Clase07.ipynb](https://github.com/daniopitz/visualizacion/blob/main/clases_practicas/clase07.ipynb) (Daniela Opitz, Profesora del ramo)
- 	[Clase08_actividades.ipynb](https://github.com/daniopitz/visualizacion/blob/main/clases_practicas/clase08_actividades.ipynb) (Daniela Opitz, Profesora del ramo)
- 	[Clase10.ipynb](https://github.com/daniopitz/visualizacion/blob/main/clases_practicas/clase10.ipynb) (Daniela Opitz, Profesora del ramo)
-  [Netflix Movies and TV Shows - EDA](https://www.kaggle.com/code/lp2595/netflix-movies-and-tv-shows-eda) (visualizaciones del dataset en Kaggle)

Por último, si bien el dataset está incluido en la carpeta "[Netflix](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/tree/main/Netflix)" de este repositorio, puede acceder al dataset completo [aquí](https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows/)
