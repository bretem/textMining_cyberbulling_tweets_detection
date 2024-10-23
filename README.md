# Text Mining Classification Cyberbulling Tweets
![image](https://github.com/user-attachments/assets/c7c566c4-ceae-479c-889d-32bdde63649f)
## Descripción
El acoso ha existido desde el principio de los tiempos, pero las formas de acoso han cambiado con el paso de los años, desde el acoso físico hasta el acoso cibernético. Debido al aumento masivo de contenido web generado por los usuarios, en particular en las redes sociales, la cantidad de discursos de odio aumenta constantemente. El discurso de odio en línea se ha vinculado a un aumento global de la violencia hacia las minorías, incluidos tiroteos masivos, linchamientos y limpieza étnica.
Este proyecto presenta una revisión sistemática de algunas investigaciones publicadas sobre los enfoques de detección del acoso cibernético y examina los métodos para detectar el discurso de odio en las redes sociales, al tiempo que lo distingue de las blasfemias en general, y realiza un estudio comparativo de varios algoritmos supervisados, incluidos los métodos estándar y de conjunto.
## Dataset
Uno de los mayores problemas en el internet de hoy en día es la presencia de actitudes negativas hacia algunos colectivos en relación a su etnia, género, religión o ideología política. En este ejercicio trabajaremos con un conjunto de datos reales, etiquetados manualmente, procedentes de la plataforma Kaggle. Originalmente, a cada documento del dataset se le asignó una de las siguientes categorías:

•	religion

•	age

•	ethnicity

•	gender

•	other_cyberbullying

•	not_cyberbullying

El objetivo inicial del dataset era su uso para entrenar un modelo capaz de detectar el tipo de contenido de odio presente en internet según el colectivo al que se atacaba. 
En este caso, para simplificar el ejercicio, se ha generado una función load_prepare_data() que cambia las categorías del dataset obteníendose al final 2 categorías con valor 1 o 0, indicando si el tweet tiene contenido de odio.

## Modelos
•	Logistic
•	Gaussian
•	RandomForest
## Modelos pre-entrenados
•	XLnet


## Conclusión
La evaluación de los resultados muestra que entre los modelos (Logistic, Gaussian y RandomForest), éste último  es el que presenta unos mejores resultados.
El modelo XLNet ajustado mostró un mejor rendimiento que el modelo RamdomForest, de ingeniería de caraácterísticas, pero no demasiado.
El modelo acertó en sus predicciones independientemente de la clase, un 85% de las veces, un 3% más que el modelo anterior.
Precisión: 55%: esta precisión indica la capacidad del modelo para identificar y categorizar correctamente los casos de cyberbulling, algo superior a la del modelo Random-Forest que era de un 47%.
En general las métricas de este modelo mejoraron el anterior, pero no en demasía, tendríamos que seguir entrenando y ajustando parámetros para mejorarlo, si bien es cierto que los resultados no están mal, habría que mejorar la precisión del mismo.
