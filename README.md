# Predecir-porttiles-con-Spark

# Introducción.

Realizar procesado de datos con Spark para luego crear un modelo de aprendizaje capaz de predecir los precios que tendra un portatil segun sus componentes.

# Objetivo

Aprender mas sobre Spark y poder utilizarlo en el futuro para limpieza de bases de datos y creación de modelos de aprendizaje.

# Estructura.

En [Notebooks](https://github.com/AdrianNiet/Predecir-porttiles-con-Spark/tree/main/Notebooks) estan todos los notebook de prueba con el primer fichero de data, todos los que empiezan con *spark* son los primeros pasos y prueba de la sintaxis con Spark.

Una vez visto la sintaxis, se realizó la limpieza de datos en [manipulation_df](https://github.com/AdrianNiet/Predecir-porttiles-con-Spark/blob/main/Notebooks/manipulation_df.ipynb), la creación del modelo se hizo en el notebook [modelo](https://github.com/AdrianNiet/Predecir-porttiles-con-Spark/blob/main/Notebooks/modelo.ipynb)

# Errores encontrados.

Primero, la creación de sesión en spark, esto tuvo complicaciones con un error relacionado con java, al re-instalarlo y reiniciar visual studio, se resolvio.

Otro error importante fue a la hora de guardar la DF limpiada, ya que, al usar windows no encontraba el HADOOP, para solucionar esto, se accedio a la pagina oficial de HADOOP, se descargo el paquete y se añadio al PATH de forma manual.
