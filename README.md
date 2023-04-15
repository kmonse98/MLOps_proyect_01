# <h1 align=center>**`Machine Learning Operations (MLOps)`**</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/67664604/217914153-1eb00e25-ac08-4dfa-aaf8-53c09038f082.png"  height=300>
</p>
¡Bienvenidos a mi primera practica de Data Science: Proyecto 01!

<hr>

A continuación una guia sobre los archivos de los que dispone este proyecto:

1.- Carpeta **ratings** Contene:

* 8 archivos csv nombrados con números del 1 al 8 los cuales constan de los puntajes de evaluación de los usuarios para peliculas y Tv_shows de las distintas platafomas: Netflix, Disney, Hulu, Amazón Prime.<br>
* El archivo **ratings.ipynb** en el cual se hizo el ETL de los archivos arriba mencionados.<br>
* El archivo **score_set.csv** el cual es un machote de los identificadores de las distintas peliculas y tv shows y su respectivo puntaje (score) promedio.
  
2.- Carpeta **DataSets** Contiene:

* 4 archivos csv de las plataformas de streaming: Amazon, Disney, Netflix y Hulu. Los cuales son cada uno un machote de datos relacionados a películas y TV shows.<br>
* El archivo **ETL.ipynb** en el que se realizó el ETL de los 4 archivos csv.<br>
* El archivo **score_set.csv** que usamos en el proceso del ETL para obtener la columna score
* El archivo **movie_set.csv** resultado del ETL

3.- carpeta **FastAPI**

* El archivo **Querys_Testeo.ipynb** contiene un testeo de las funciones que serán usadas en la fastAPI:
* **main.py** es el archivo principal vinculado a la fastAPI.
* **movie_set.csv** es nuestra fuente de datos

4.- Archivo **Eda.ipynb**:

En este archivo podemos hallar el **Exploratory Data Analysis** de la fuente de datos **movie_set.csv**

5.- Archivo **Sistema_de_Recomendación.ipynb**

En el podemos encontrar un sistema de recomndación dado un usuario y una id de pélicula.


