Requerimientos ✅❌
  * ✅Un resumen del proyecto.
  * ❌Las cinco o más visualizaciones (al menos tres de alta complejidad y dos de baja complejidad) con una breve explicación de cada una.
  * ✅Créditos a todos los integrantes del grupo.
  * ✅Todos los datos utilizados para el proyecto (puedes incluirlos directamente proporcionar enlaces a los datos si son muy grandes).
  * ❌Enlaces a todos los códigos que se usaron como base del proyecto, dandolos créditos correspondientes

Este proyecto, se basa en el análisis de la base de datos de la producción de películas de Netflix, con el objetivo de Identificar patrones y tendencias de producción de películas en diferentes zonas geográficas, y analizar la evolución del catálogo y evaluar la diversidad en el contenido de Netflix. Todo esto a través de visualizaciones y el análisis de ellas.

En este proyecto, los colaboradores fueron Renato Fernández, Valentina Jiménez, Sebastián Ramírez y Vicente Ramírez. Con la supervisión y ayuda de la docente guía Daniela Opitz.

Se utilizó únicamente dataset llamado Netflix Movies and TV Shows, Exploring the Depths of Netflix: A Comprehensive Dataset of Movies and TV Shows
Proporcionado por M Rahul Vyas, Artificial Intelligence Engineer
Cuyo link de descarga es: https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows/code

# Proyecto: Análisis de Películas en Netflix (2008-2021)

## Resumen

Este proyecto se desarrolla en el marco del curso **Taller de Visualización de la Información**. Su objetivo es realizar un análisis exhaustivo de las películas que han sido subidas a la plataforma de streaming Netflix desde el año 2008 hasta el 2021.

## Objetivo del Proyecto

El principal objetivo de este proyecto es identificar y analizar los tipos de películas que han sido más subidas a Netflix durante el período mencionado. A partir de este análisis, se busca:

1. **Análisis Directo**: Determinar los géneros y tipos de películas más producidos y subidos a Netflix. Esto permite comprender las tendencias en la producción de contenido audiovisual en la plataforma.

2. **Análisis Indirecto**: Inferir patrones de consumo de los usuarios de Netflix a través del análisis de la oferta de películas. Al identificar qué tipo de contenido se sube con mayor frecuencia, se pueden hacer suposiciones sobre las preferencias y hábitos de consumo de los usuarios.

## Contenidos del Proyecto

El proyecto incluye los siguientes componentes:

- **Recopilación de Datos**: Recolección de datos sobre las películas disponibles en Netflix desde 2008 hasta 2021.
- **Limpieza de Datos**: Procesamiento y depuración de los datos recolectados para asegurar su calidad y fiabilidad.
- **Visualización de Resultados**: Creación de gráficos y visualizaciones para presentar los hallazgos de manera clara y comprensible.
- **Conclusiones**: Interpretación de los resultados obtenidos y discusión sobre las implicaciones del análisis tanto para la producción como para el consumo de material audiovisual en Netflix.

## Herramientas y Tecnologías

El proyecto utiliza una variedad de herramientas y tecnologías, incluyendo:

- **Películas vs series**: Para determinar cuantas películas y series hay en el dataset.
![CantPeliculaSerie](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/22ab995e-4317-4663-abd0-25473baa5df1)

- **Top Categorías**: Para determinar las categorías más repetidas.
![top_categorías](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/c5ecd975-d997-4dc0-a622-c844d4cfb181)

- **Top Países**: Para determinar los países más repetidos.
![top_paises](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/8227383f-e026-4193-a681-2f5c57810fd4)

- **Top Países Storyline**: Para determinar los países más repetidos como evolución del tiempo.
![top_paises_storyline](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/05216bc7-11f6-4a66-986c-3dc48d008d07)
![top_paises_acumulado_storyline](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/2d6b1d18-41d0-441d-9513-8a6ca2cd01cb)

- **Proveniencia top 3**: Para determinar de donde vienen las películas de las categorías más vistas.
![Proveniencia_peliculas_drama](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/0aae5733-5080-496f-a9ea-a6a390d8f94d)
![Proveniencia_peliculas_internacionales](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/9003269c-30ae-40fa-958e-638aa4dfa0a0)
![Proveniencia_peliculas_comedia](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/78755db2-861a-49f9-bfb7-5146b9032581)

- **Entropía**: Para determinar la variación de las categorías en función del tiempo.
![Entropia](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/a1ceb77a-ab40-4225-817d-3f504d5a018a)

- **Películas por año**: Mapa de calor acerca de las películas y su categoría por año
![hm_genre_per_year](https://github.com/sebvitaa/Analisis-del-contenido-de-Netflix/assets/173504446/a2d7327d-05cd-47a3-a706-ecad48f7b266)

## Visualizaciones obtenidas

- **Python**: Para la manipulación y análisis de datos.
- **Pandas**: Para la limpieza y análisis de datos.
- **Matplotlib y Seaborn**: Para la creación de visualizaciones estáticas.
- **Jupyter Notebooks**: Para documentar el proceso de análisis y las visualizaciones.

## Conclusión

Este proyecto proporciona una visión detallada sobre las tendencias de producción y consumo de películas en Netflix desde 2008 hasta 2021. A través del análisis y la visualización de datos, se puede entender mejor qué tipo de contenido domina la plataforma y cómo esto puede
