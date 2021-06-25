#### ProyectoBigData
# TRABAJO PRÁCTICO DE BIG DATA 🖱️

El objetivo del proyecto es trabajar con grandes volúmenes de datos con aplicabilidad directa al mundo empresarial. Para el trabajo se optó por evaluar a la empresa Coca Cola, debido al acontecimiento reciente en una conferencia de prensa que causó un impacto importante surgiendo así el interés por analizar la imagen corporativa de la misma.

## Contenido del Proyecto 📑

Este proyecto alberga como archivos: el código fuente (en dos formatos: .py y .ipynb) y dos datasets. Y se divide en 2 partes:

### Primera Parte: Data Fetching

Recopilación de datos de la red social [Twitter](https://twitter.com/) utilizando web scraping, la API de Twitter y el lenguaje Python.

**1. Extracción de datos**

Obtención de una lista de las últimas menciones del hashtag #CocaCola teniendo como *primera salida un archivo (.csv)* para su posterior análisis.

### Segunda Parte: Data Analysis

Análisis de sentimientos de publicaciones en redes sociales para evaluar la imagen de la empresa, cuyos resultados se visualizan a través de gráficos o wordcloud. Además, un cálculo del sentimiento promedio relacionado a las menciones.

**1. Modelo de clasificación**

- VADER

Para el análisis de sentimientos se realizó una prueba previa entre dos algoritmos, TextBlob y VADER para observar los resultados, sin embargo, se descartó el uso de TextBlob debido que VADER muestra un mejor funcionamiento con los textos de las redes sociales y también en general, basándose en léxicos de palabras relacionadas con el sentimiento.

**2. Limpieza y gráficos**

Eliminación de Tokens no relevantes para obtener posteriormente representaciones gráficas de los resultados obtenidos del análisis (Wordcloud especialmente). 

_El segundo archivo de salida (.csv) cuenta con datos limpios y el análisis de sentimientos (puntajes de cada uno)._
 
## Comenzando 🚀 

_Las siguientes instrucciones permitirán que puedas acceder sin incovenientes a todos los componentes del proyecto en tu máquina local._

### Requisitos 📋

Para el proyecto son necesarios los siguientes:
 
- Una cuenta como desarrollador en Twitter para obtener las credenciales [(API Twitter)](https://developer.twitter.com/en) 
- Un servicio cloud para los códigos o algún IDE de tu preferencia. 

 ### Clonación 👥
Una vez creada la cuenta de github se deberá clonar el proyecto utlizando la URL y el comando:

```
git clone (url)
```

### Visualización 🧐
![image](https://user-images.githubusercontent.com/71017838/123277093-cac49180-d4d3-11eb-8520-bc2dc3b8b351.png)

### Instalación 🔧

Se utiliza el siguiente comando en caso que no se tenga alguna de las librerías necesitadas

```
!pip install (libreria)
```

### Despliegue 📦

Una vez finalizada la instalación podrás darle "Ejecutar/Run" al código fuente para obtener los resultados.

## Lenguaje de Programación 🖥️
  
  `Python` 
  
## Construido con 🛠️

_La herramienta utilizada para el scraping de una página web fue:_

* [Google Colaboratory](https://colab.research.google.com/)
* Lenguaje de Programación: [Python](https://www.python.org/)

## Autores 🖋️👥
* *Zileidy Argüello Barreto* 
* *Micaela Maldonado Otazo* 

Estudiantes del 3er. año de la carrera Tecnologías de la Información Empresarial (UPA)

## Observaciones 🖋️❗
Fecha de creación del código: 24/06/2021

Es posible que algunas características cambien conforme pasa el tiempo.

## Gracias por mirar este proyecto 📢🤓

