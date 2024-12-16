# analisis_de_plataformas_de_videojuegos
# Introducción
Analizaremos La tienda online Ice vende videojuegos por todo el mundo.Esto nos permitirá detectar planificar campañas publicitarias.
Las reseñas de usuarios y expertos, los géneros, las plataformas y los datos históricos sobre las ventas de juegos están disponibles. 
Vamos a identificar patrones que determinen si un juego tiene éxito o no. 
Esto nos permitirá detectar planificar campañas publicitarias.

Hay datos que se remontan a 2016. Imaginemos que es diciembre de 2016 y planearemos una campaña para 2017.
El dataset contiene una columna `"rating"` que almacena la clasificación ESRB de cada juego. El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.
# Descripción de los datos
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
- Pudimos observar en una grafica como en 2008 y 2009 crecio de manera exponencial la cantidad de titulos de videojuegos en 1400 juegos
- Filtramos un nuevo dataframe de 5 años atras a partir de la fecha de los datos 2016.
- De ahi pudimos observar con nun diagrama de caja las 2 plataformas con mayor numero de ventas en el m,undo siendo ps3 y ps4
- Nos dimos cuenta que no habia correlación con las reseñas de usuarios ni reseñas hechas por profesionales en cuanto a las ventas con una correlación cercanas a 0.
- Tambien mediante una grafica obtuvimos los 3 mejores juegos en ventas y los 3 peores en ventas.
- Obtuvimos graficas por región con vlas mayores ventas por plataforma;
-  - **Norte America** la plataforma con mayor numero de ventas el X360
- **Japón**  la plataforma con mayor numero de ventas el 3DS 
- **Europa y resto del mundo** con mayor numero de ventas fue el PS3!!
- Obtuvimos que los juegos dirigidos a un publico maduro **Mature** de acuerdo a la clasificacion ESRB obtuvieron las mayores ventas exceptuando a Japon donde habia más ventas a un publico infantil **Everyone**
## Hipotesis
De acuerdo a nuestras dos hipotesis:
- **Hipótesis 1:** Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
- Hipótesis nula (H0): Las calificaciones promedio de los usuarios para Xbox One y PC son iguales.
- Hipótesis alternativa (H1): Las calificaciones promedio de los usuarios para Xbox One y PC son diferentes.
  
  RESULTADO:_obtuvimos  Las calificaciones promedio de los usuarios para Xbox One y PC son diferentes
  
- **Hipótesis 2:** Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
-Hipótesis nula (H0): Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son iguales.
-Hipótesis alternativa (H1): Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
  
  RESULTADO: obtuvimos Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son iguales.

NOTA: PARA AMBAS UTILIZAMOS LA PRUEBA DE T STUDENT Y COMPARAMOS EL VALOR P
