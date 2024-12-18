# Análisis_de_plataformas_de_videojuegos
# Introducción
Analizaremos La tienda online Ice que vende videojuegos por todo el mundo.Esto nos permitirá detectar y planificar campañas publicitarias.
Las reseñas de los usuarios y expertos, los géneros, las plataformas y los datos históricos sobre las ventas de juegos están disponibles. 
Vamos a identificar patrones que determinen si un juego tiene éxito o no. Los datos se remontan a 2016. 
Resolveremos nuestras dos hipotesis que nos planteamos:
- Hipótesis 1: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
- Hipótesis 2: Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.



# Descripción de los datos
El dataset contiene una columna `Rating` que almacena la clasificación **ESRB** de cada juego (Entertainment Software Rating Board) evalúa el contenido de un juego y asigna una clasificación por edad como Adolescente o Adulto.

- `Name` (Nombre)

- `Platform` (Plataforma)

- `Year_of_Release` (Año de lanzamiento)

- `Genre` (Género) 

- `NA_sales` (ventas en Norteamérica en millones de dólares estadounidenses) 

- `EU_sales` (ventas en Europa en millones de dólares estadounidenses) 

- `JP_sales` (ventas en Japón en millones de dólares estadounidenses) 

- `Other_sales` (ventas en otros países en millones de dólares estadounidenses) 

- `Critic_Score` (máximo de 100) 

- `User_Score` (máximo de 10) 

- `Rating` (ESRB)

# Habilidades técnicas
- Phyton
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Preprocesamiento de datos
- Análisis exploratorio
- Análisis estadistico

# Conclusión General
- Pudimos observar en una grafica de barras como en 2008 y 2009 creció de manera exponencial la cantidad de titulos de videojuegos creados (**1400 juegos**).
- Filtramos un nuevo Dataframe con datos del 2011 al 2016.
- Apartir de nuestro nuevo Dataframe realizamos un diagrama de caja, visualizamos las 2 plataformas con mayor numero de ventas en el mundo siendo **ps3 y ps4**.
- No encontramos correlación con las ventas y las reseñas hechas por usuarios y por profesionales. 
- Mediante una grafica de barras obtuvimos:.
- Los 3 mejores juegos en ventas:
- -
- -
- -
-  Los 3 peores en ventas:
-  -
-  -
-  -
- Realizamos visualizaciones para observar cuales plataformas reportaban mayores números de ventas por Región: 
-  - **Norte America** plataforma con mayor numero de ventas **X360**
-  - **Japón**  plataforma con mayor numero de ventas **3DS** 
-  - **Europa y resto del mundo** mayor numero de ventas **PS3**
- Obtuvimos que los juegos dirigidos a un publico maduro **(Mature)** de acuerdo a la clasificación **(ESRB)**  obtuvieron las mayores ventas en casi todas las regiones! con excepción de nuestro pais nipon 'Japon' donde habia más ventas dirigido a un público para todas las edades **Everyone**
## Hipotesis

- **Hipótesis 1: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.**
- - Hipótesis nula (H0): Las calificaciones promedio de los usuarios para Xbox One y PC son iguales.
- - Hipótesis alternativa (H1): Las calificaciones promedio de los usuarios para Xbox One y PC son diferentes.
  
  RESULTADO: obtuvimos que las calificaciones promedio de los usuarios para Xbox One y PC son diferentes
  
- **Hipótesis 2: Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.**
- - Hipótesis nula (H0): Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son iguales.
- - Hipótesis alternativa (H1): Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
  
  RESULTADO: obtuvimos que las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son iguales.

NOTA: PARA AMBAS UTILIZAMOS LA PRUEBA DE T STUDENT Y COMPARAMOS EL VALOR P.
