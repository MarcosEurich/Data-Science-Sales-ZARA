# Data-Science-Sales-ZARA
Analisis  EDA y Machine Learning sobre las ventas historicas de la cadena de tiendas ZARA
# <a name="_9fk2i19obqxg"></a>1 Introducción

`	`El siguiente proyecto de Machine Learning se centra en el análisis de las Ventas de la empresa de indumentaria ZARA, con sede en España. En el mismo será hará un análisis profundo de los datos y transformación de ser necesario aplicando las metodologías EDA y ETL con los datos generales

`	`Posteriormente analizaremos la variable objetivo “Sales Volume” viendo su relación con el resto de las variables y sus comportamientos en diferentes escenarios como region,sexo,etc.

# <a name="_atambajy0mnj"></a>2 Resumen de metadata
`	`Los datos analizados están compuestos por las siguientes variables:

|Nombre Campo|Cant. Registros|Valores Nulos|Tipo de dato|
| :- | :- | :- | :- |
|Product ID|20252|no-null|int64|
|Product Position|20252|no-null|object|
|Promotion  |20252|no-null|object|
|Product Category|20252|no-null|object|
|Seasonal |20252|no-null|object|
|` `Sales Volume |20252|no-null|int64|
|` `brand     |20252|no-null|object|
|url   |20252|no-null|object|
|name |20252|no-null|object|
|description|20252|no-null|object|
|price |20252|no-null|float64|
|currency    |20252|no-null|object|
|terms |20252|no-null|object|
|` `section |20252|no-null|object|
|season |20252|no-null|object|
|material|20252|no-null|object|
|origin|20252|no-null|object|


`	`Como podemos observar en la tabla el datasets presenta 17 campos o variables diferentes con 20252 registros cada una y sin datos nulos.


# <a name="_xzvan47d8h8m"></a>3 Preguntas hipótesis y Objetivo

En este proyecto se abordará un análisis exhaustivo sobre las ventas de indumentaria de la cadena ZARA como así también su relación con otras variables. El dataset está compuesto por la venta de cada uno de sus productos con su precio,genero,estacion,cantidad de ventas

**HIPÓTESIS**

1- Cuánto productos según estación se venden por temporada?.

2- Cuántos productos según género se vende por temporada?

3-Analizar las ventas por género y origen del material?

4-¿Qué relación hay entre el género y el tipo de producto?

5-Qué relación tienen los productos de temporada con las ventas?


# <a name="_xr51u9atx5xs"></a>4 Insights

**Hipótesis 1:**

Podemos observar como en la temporada de Otoño (Autumn) las ventas son muchas significativas, como así también que en verano (summer) caen drásticamente.

**Hipótesis 2:**

Observamos que las Mujeres (Woman) compran más que los hombres (Man) y que los picos de ventas son en invierno (winter) para ambos sexos, sin embargo como vimos en el gráfico 3.1 en total de USD no es así.

**Hipótesis 3:**

Visualizamos que los productos más vendidos son de mujeres y los principales orígenes de los mismo son Bangladesh y China


**Hipótesis 4:**

Al aplicar una correlación Biserial Puntual, obtuvimos un coeficiente de -0.005 con un p-value de 0.43. Dado que el p-value es mayor a 0.05, concluimos que no existe una relación significativa entre el género y el precio. Esto indica que ZARA mantiene una estrategia de precios homogénea, donde los productos de hombres y mujeres tienen rangos de costos similares

**Hipótesis 5:**

`	`Los productos de temporada tienen un volumen de ventas promedio superior (aprox. +14.5%) a los productos no estacionales.

-El gráfico de caja muestra claramente que la mediana de ventas (la línea dentro de la caja) es más alta para los productos "Seasonal" (Yes) que para los "No Seasonal.

Sin embargo como la diferencia porcentual en el promedio de las ventas no es tan elevado es más probable que se venda pero no es una garantía ni mucho menos

