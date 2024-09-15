#### Sistema de Detección de Spam en URLs
Este proyecto desarrolla un sistema para identificar automáticamente si una URL es spam o no utilizando técnicas de NLP y un modelo SVM (Support Vector Machine).

#### Desarrollo del Proyecto
Carga de Datos: Utilizamos un archivo llamado url_spam.csv que contiene URLs etiquetadas como spam o no spam.
Preprocesamiento: Limpiamos las URLs y las convertimos en una forma numérica utilizando el método TF-IDF.
Entrenamiento del Modelo: Entrenamos un modelo SVM con los datos procesados para que pueda clasificar nuevas URLs como spam o no spam.
Optimización: Ajustamos los parámetros del modelo con GridSearchCV para mejorar su rendimiento.
Resultados: El modelo optimizado alcanzó una precisión del 96.67% y mejoramos la detección de spam de un 83% a un 90% en el recall.
### Resultados Finales
Accuracy: 96.67%
Recall para spam: 90%
El modelo entrenado se guarda en la carpeta models y está listo para ser usado en futuras predicciones.