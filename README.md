# Titanic - Machine Learning from Disaster
Compito en la caso práctico de Kaggle [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

El objetivo de realizar este trabajo es mejorar mis habilidades en ciencia de datos y continuar familiarizandome con las librerías de python. En este trabajo se realiza depurado y exploración de datos, además busco el mejor modelo e identifico sus hiperparámetros ótpimos.
Las librerías utilizadas son Pandas, Matplotlib, Seaborn, Pycaret, Scikit Learn y imbalancedlearn. 

Comienzo por depurar y explorar los datos para comprender las variables. Luego de tener los datos limpios, aplico ingeniería de datos para crear nuevas variables que ayuden a los modelos. Para seleccionar el modelo utilizo Pycaret y Sklearn, ambas liberías indican que la los mejores modelos para este caso son Gradient Boosting Classifier y Light Gradient Boosting Machine Classifier. Luego de buscar los hiperparametros óptimos mediante RandomizedSearchCV y realizar una validación cruzada de 15 pliegues, la precisión más alta fue encontrada con en ambos casos entorno al 85%. 
