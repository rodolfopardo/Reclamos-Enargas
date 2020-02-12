## Reclamos resueltos por Enargas en el período 2018 - 2019

El ENARGAS actualizó hace un par de días en la página de datos abiertos de la República Argentina una base de datos dónde muestra todos los reclamos resueltos durante el año 2018 y 2019. En MDZ, decidimos meternos de lleno en el detalle de lo presentado utilizando a Python como lenguaje de programación para la limpieza y exploración de los datos.

El dataset contiene cantidad de reclamos por delegación degional/dede Central, prestadora, tipo, origen y mes/año. Algunos parámetros venían algo distorsionados en cuanto al tipo de variable pero pudimos realizar una correcta transformación de los datos que nos permite arrojar los siguientes resultados estadísticos.

**Reclamos resueltos por año**

En 2018, Enargas resolvió una cantidad de 9697 reclamos mientras que en 2019 se realizaron 9893. Esto significa que los reclamos aumentaron en comparación de un año con otro. 
![](https://www.datocms-assets.com/21842/1581507950-descarga-6.png)

Al analizar las máximas de los reclamos, podemos encontrar dos casos llamativos ocurridos en el mes de junio y julio respectivamente: 

En 2018, se registraron un total de 299 reclamos por "Falta de suministro de gas" en pleno invierno (mes junio). 

En 2019, pasó algo muy parecido pero fueron 281 casos, también registrados en pleno invierno (mes julio).

![](https://www.datocms-assets.com/21842/1581507996-captura-de-pantalla-2020-02-12-a-la-s-08-09-42.png)


**Cantidad de reclamos por mes**

Partamos este análisis desde una hipótesis que afirma que los meses correspondientes a la estación de invierno son los que más reclamos generan. Ahora, midiendo los mismos, vamos a observar si refutamos o no a la misma. 

En este gráfico se puede observar como Julio, Agosto y entrada la primavera de Octubre son los meses más populares.
![](https://www.datocms-assets.com/21842/1581508026-descarga-7.png)


Distinta son las cosas si nos centramos en la media (promedio) de reclamos por mes. Es aquí, donde prioriza los meses de invierno pero no nos termina de confirmar la hipótesis.

![](https://www.datocms-assets.com/21842/1581508056-descarga-8.png)

Para evidenciar muestras, es correcto utilizar la máxima de los valores registrados por mes. Es aquí donde podemos confirmar la hipótesis planteada al comienzo de este análisis.

![](https://www.datocms-assets.com/21842/1581508082-descarga-9.png)

**Medios de reclamos más utilizados**

Resulta llamativo que en la revolución tecnológica que estamos viviendo, sigamos confiando en el teléfono como el medio más importante del usuario para realizar el reclamo. Esto se debe a dos cosas, una la confianza que genera el teléfono ya sea celular o fijo, escuchar a alguien del otro lado es sentir la humanización de la marca, y la otra es la falta de información de los organismos ante otras vías de reclamos propuestas para solucionar los mismos de manera más ágil. 

Esta muestra debería ser más "normalizada" si la empresa realiza de manera correcta la comunicación de todas sus vías de reclamo. 

![](https://www.datocms-assets.com/21842/1581508132-descarga-10.png)


**Reclamos por distribuidora**

En lo que respecta a Cuyo, la Distribuidora Gas Cuyana ha resuelto 1984 denuncias ocupando el tercer lugar. Este es el ranking nacional: 

![](https://www.datocms-assets.com/21842/1581508164-captura-de-pantalla-2020-02-12-a-la-s-08-29-32.png)

El Centro Regional Cuyo, como sedes de Enargas, también ocupa el tercer lugar. 

**Tipos de reclamo**

Por último, analizamos la última variable que nos provee este dataset y corresponde al tipo de reclamo realizado. 

Podemos observar cómo "Inconvenientes en el suministro de gas" es el más popular de los reclamos resueltos con un total de 11221. Lo sigue "Facturación y reclamo de deudas" con 5845. 

![](https://www.datocms-assets.com/21842/1581508231-descarga-14.png)
