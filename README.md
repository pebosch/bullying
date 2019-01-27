# Bullying
Software para el Análisis Inteligente del Acoso Escolar en las Redes Sociales

Contenido de la carpeta "data"
-----

* **getTweets.py** <br />
	Código de ejemplo para obtener tweets como objetos JSON a partir de una lista de ID de tweets.

* **tweet_id** <br />
	Contiene una lista con los ID de los tweets utilizados en este trabajo. Pueden ser recuperados mediante el fichero getTweets.py.

* **data.csv** <br />
	Cada línea de este fichero corresponde a un tweet y tiene dos campos 
	separados por comas: <"id-tweet","etiqueta">.
  Los posibles valores para el campo binario "etiqueta", son: 
  * (1) Positivo o Bullying 
  * (2) Negativo o No bullying

Contenido de la carpeta "weka-algorithms"
-----

* **lr _(Linear Regression o Regresión Lineal)_**
  - Modelo de clasificador lr.
  - Resultados tras aplicar el modelo de clasificador lr.
* **mnb _(Multinomial Naive Bayes)_**
  - Modelo de clasificador mnb .
  - Resultados tras aplicar el modelo de clasificador mnb.
* **rf _(Random Forest o Bosques Aleatorios)_**
  - Modelo de clasificador rf.
  - Resultados tras aplicar el modelo de clasificador rf.
* **svm _(Support Vector Machines o Máquinas de Vectores de Soporte)_**
  - Modelo de clasificador svm.
  - Resultados tras aplicar el modelo de clasificador svm.
* **weka-datafile.arff**
  - Fichero origen de los datos.


Referencias
-----

*Análisis Inteligente del Acoso Escolar en las Redes Sociales.* <br />
*Pedro Fernández(1,2), Jesús Estrella(2), Alberto Guillén(1)* <br />
*1 Departamento de Arquitectura y Tecnología de los Computadores, Universidad de Granada, España.* <br />
*2 Departamento de Orientación, Colegio Amor de Dios, Almería, España.* <br />
*E-Mail: pedro@andared.es, jesuseh@amordiosal.com, aguillen@ugr.es*
