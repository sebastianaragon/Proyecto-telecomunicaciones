# Proyecto-telecomunicaciones
Analisis descriptivo de KPIS (Indicadores de medición de celdas) de la red de telecomunicaciones. Partimos de un registro extenso el cual viene dados por mas de 3600 indicadores con una granularidad de 5 minutos, es decir, cada 5 minutos estos indicadores recopilan el estado de funcionalidad.
El objetivo es optimizar toda esta informacion con el fin de reducir indicadores a los mas relevantes, esto realizado por medio de modelos predictivos.

# Objetivos
Se requiere una metodologia de analisis automatizable que permita perfilarlas celdas segun su capacidad,  adicionalmente, identificar de forma automatica cuales son las variables de mayor o menor impacto en la capacidad y ocupacion de cada una de las celdas.
* __Automatizacion de tareas__
* __Mejora de la precision y calidad de los datos__
* __Prediccion de patrones y tendencias__
* __Creacion de un modelo escalable__

# Proceso
* __1__: [Recopilacion de datos]
* __1__: [Preparacion de datos]
* __1__: [Analisis exploratorio de datos]
* __1__: [Analisis estadistico]
* __1__: [Modelado de datos]
* __1__: [Interpretacion de resultados]

# Conclusiones

Identificamos que las columnas de 'L.Traffic.Sch.DL.Num' , 'L.Traffic.Schedule.Dedicate.AVf' y 'L.Traffic.Pktinterval.Num' Fueron las fuentes de datos mas representativas al momento de realizar nuestro modelo 'Random Forest' en el cual obtuvimos un error del 2.8% En la precision. Encontramos que con estas fuentes de datos podemos predecir con exactitud que tantos recursos usara en promedio nuestras celdas.
Por temas de tiempo y memoria limitada de nuestro entorno de trabajo, segementamos las columnas para usar unicamente 50, de las mas de 1000 columnas con las cuales pudimos haber usado para nuestro modelo, es decir nuestro modelo es escalable.

