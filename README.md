# TP-2--Redes-Neuronales-Laguinge-Moya-Piacentino

Los scripts que están subidos corresponden a:

- TP2-Modelo: tiene todo la creación de las capas del modelo, el entrenamiento, los distintos de validación (hold out y time cross series validation), la predicción del modelo, la creación y la elección de los mejores parámetros. 
- TP2-Modelo prueba con mejores parametros: en este script se muestra la corrida del modelo que dio mejor score. 
- Helper: Todas las funciones utilizadas en los demás scripts
- TP2-Detalle de funciones del Helper: Se explican todas las funciones del Helper utilizadas para los embeddings, creación del modelo, entrenamiento, obtención de métricas y métodos de validación. 
- Elección características y parámetros: aca se muestra el proceso de selección de características para lograr un mejor score. 
- Creación de csv para Results que falto: debido a que se intento entrenar 100 modelos al mismo tiempo, el collab se paro, pero se lograron entrenar 30 modelo con distintas características. En este script se levantan estos 30 modelos para obtener los scores y evaluar la selección de características. 
-  TP2 Analisis dataset y preprocesamiento: acá se analizan los datasets, se los procesa y agregan características para la posterior creación del modelo.
-  TP2-Analisis de Embeddings y Resultados: acá se analizan los embeddings. 

En las carpetas:
- submission: se encuentran todos los submissions creados que fueron subidos al kaggle. 
- resultados: se muestran los resultados obtenidos entrenando a los modelos con distintas características. 
- elección características: están los scripts que corrimos para entrenar modelos con distintas características y obtener el mejor score y la carpeta resultados en donde están los resultados obtenidos para cada script.
