
# Práctica 3 | Visualización de gráficos

<p align = "justify">
Para la tercera práctica he realizado tres gráficos con los datos de Tresca con el objetivo de realizar una visualización de la variación de los datos en el tiempo. En este caso, he organizado los datos más relevantes de tres periodos estacionales, en primavera, en verano, y en invierno. Para extraer los datos que necesitaba he recurrido a Openrefine y Excel y para visualizarlos de forma gráfica he utilizado Datawrapper.</p>

## Proceso de realización de práctica

Para realizar estos gráficos he llevado a cabo el mismo procedimiento con rangos de fechas distintos, por tanto voy a explicar cómo he ejecutado este proceso de selección y visualización de datos y posteriormente analizaré los resultados obetenidos con estos gráficos. 

En primer lugar, he introducido los datos del archivo _Feliz_ de _Tresca_ en Open Refine en formato _csv_, he seleccionado la separación por comas, he eliminado la opción "use character" y "parte next" y se ha creado a continuación un proyecto de 5981 filas. Después eliminé los datos que aparecían del año 1970 con una faceta de línea de tiempo y me he quedado, por tanto, con 5971 filas. 

Posteriormente he seleccionado los datos que me interesaban en Openrefine, mendiante la selección de tiempo para realizar los tres gráficos correspondientes. Y para ello, antes de nada he convertido la columna fecha en *formato fecha*, ya que tenía *formato de texto* y de esta manera no se podían filtrar los datos. Por tanto, una vez cambiado el formato he procedido a filtrar los datos del archivo por sus respectivas fechas y los he organizado   de forma conceptual por estaciones. Además he eliminado las columnas que ya sabía que no iba a utilizar llegado a este punto, que eran la 4 y la 5. También, en la columna 6, añadí el número 0 en los espacios vacíos, pero luego no utilicé esa columna.

A partir de esto, decidí organizar los gráficos con el concepto de temporadas estacionales, sin embargo, esta organización no corresponde exactamente con los periodos estacionales oficiales, sino que comprenden los meses aproximados en los que predominan estas estaciones y por esta razón las he titulado con estos términos. De manera que, la organización temporal de los gráficos corresponde, en el primer  gráfico a la época de **primavera** y contiene la organización de los _hastags_ mencionados en tweets que comprenden los meses entre marzo y junio de 2020. El segundo gráfico titulado **Verano**, contiene todos los _hastags_ publicados entre los meses de junio y septiembre de 2020, y por último el gráfico de **Invierno** contiene los _hastags_ publicados de noviembre de 2020 a enero de 2021.


Seguidamente, en la columna de los _hastags_ he utilizado la función _facetfound_ para contar todos los tweets que tuvieran las mismas palabras, es decir el mismo _hastag_ repetido. Esto me ha generado una nueva columna en la que aparecía el recuento de las veces en las que se repetían los tweets correspondientes. Depués, estos datos los he exportado en formato _csv_ a Excel.


En Excel, primero he quitado los valores repetidos en _anular duplicados_, para quedarme con sólo con una representacion de cada tweet y para plasmarlo en el gráfico de forma visual. Después los he ordenado de mayor a menor número de repeticiones y he seleccionado los 20 más relevantes, es decir, los mas repetidos de cada seleccion de datos. 

Por último, despues de seleccionar y guardar estos datos en Excel (en formato _csv_), he importado estas hojas de Excel en Datawrapper en la opción _upload data_ y para obtener el gráfico que  buscaba, he escondido las columnas que no me interesaban con la opción de _Hide column from visualization_, en este caso para quedarme solo con los tweets y sus repeticiones. Por tanto, se ha realizado el gráfico correspondiente con los datos introducidos, he cambiado el nombre de cada uno para titularlos con sus características. Y por último, para representarlos he elegido el grafico de barras en los tres para llevar a cabo un mejor analisis comparativo.


## Resultado Gráficos

El objetivo de la selección de estos datos es observar la difencia de las felicitaciones y de las festividades según el avance temporal del año, en un aspecto generalizado.

### Gráfico 1

![alt text](https://github.com/luciahdezg/uc3m-periodismo-datos/blob/main/Imagenes/gla9d-tweets-primavera.png)

En el primer gráfico predominan las felicitaciones de los días de la semana, en cabeza en el gráfico. Continua con felicitaciones generales y también las correspondientes con el Día del Padre y el Día de la madre que se encuentran en este espacio temporal, puesto que son el el mes de marzo y mayo, respetivamente. Finalemente, en los últimos aparece de forma escasa alguna felitación de la Pascua de Resurrección.

### Gráfico 2 

![alt text](https://github.com/luciahdezg/uc3m-periodismo-datos/blob/main/Imagenes/L58RC-tweets-verano-br-.png)

En los tweets correspondientes a los meses de verano, predomina de nuevo las felicitaciones a los días de la semana, algunas correspondientes a festividades fuera de estas fechas y también algún feliz cumpleaños, en el que se habrá viralizado el _hastag_ correspondiente.

### Gráfico 3

![alt text](https://github.com/luciahdezg/uc3m-periodismo-datos/blob/main/Imagenes/MfiXz-tweets-invierno-br-.png)

En este último gráfico, de nuevo predominan las felicitaciones a los días de la semana, muy por encima del resto. Y en este caso, puesto que las fechas corresponden a las festividades de Navidad, comienzan las felicitaciones navideñas y de fin de año.

- **Conclusión**
<p align = "justify">
Analizando los tres gráficos distintos, me ha llamado la atención que predominen en todos las felicitaciones de los días de la semana. Demuestra los ánimos y la postividad con la que los twitteros frecuentes, comienzan el día de la semana. Además es curioso y parádojico que, el día que precede siempre es el martes, puesto que va unido a la mala suerte. Especialmente me resulta sorprendente que en la época de invierno no predominen las festividades navideñas o la felicitación de año, que suelen ser bastante frecuentes. En conclusión, me parece interesante analizar como a pesar de que van cambiando los intereses y las rutinas de la población, (por lo menos de la población activa en twitter) según el mes o la época del año en año en la que se encuentren, tienen en común las mismas felicitaciones durante todo el año.</p> 

