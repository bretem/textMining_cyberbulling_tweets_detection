## Detección de sentimiento en tweets

Uno de los mayores problemas en el internet de hoy en día es la presencia de actitudes negativas hacia algunos colectivos en relación a su etnia, género, religión o ideología política. En este ejercicio trabajaremos con un conjunto de datos reales, etiquetados manualmente, procedentes de la plataforma Kaggle. Originalmente, a cada documento del dataset se le asignó una de las siguientes categorías:

religion

age

ethnicity

gender

other_cyberbullying

not_cyberbullying

Se va a entrenar diferentes modelos de clasificación que permitan clasificar correctamente los tweets. Para ello será necesario crear y utilizar funciones de preprocesado de datos similares a las vistas en clase, aplicar estrategias de vectorización de trextos como TF-IDF o embeddings, y entrenar/evaluar modelos de clasificación. Para que os sirva de orientación, los criterios de evaluación del ejercicio serán los siguientes:

Análisis exploratorio, pre-procesado y normalización de los datos **: - Se va a hacer un análisis exploratorio de los datos como número de documentos, gráficas de distribución de longitudes y/o wordclouds ...

Se van a generar funciones para normalizar textos que permitan eliminar palabras vacías, quitar símbolos de puntuación y lematizar o hacer stemming.
Vectorización de textos 

Se van a usar estrategias de vectorización como TF-IDF y Word Embeddings. Será necesario incorporar características adicionales como el sentimiento o características léxicas.

Entrenamiento y validación del sistema 

En el proceso de entrenamiento del modelo se van a testear al menos 3 modelos de clasificación. El procedimiento será primero una estimación del rendimiento de varios algoritmos de forma general, para posteriormente seleccionar el mejor para ajustar los hiperparámetros.
