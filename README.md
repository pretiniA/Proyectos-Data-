# Proyecto-Analisis-crediticio
Este repositorio contiene el proyecto desarrollado en el marco del curso de Data Science de Coderhouse.
Para el mismo utilizamos una base de datos (con datos simulados) correspondiente a una entidad financiera.

**Objetivo**

* El objetivo del mismo es predecir la clase que asumirá un nuevo cliente dentro de la variable 'STATUS' (la cual hace referencia al grado de morosidad del cliente a la hora de pagar el préstamo).

**Herramientas utilizadas**

* Para realizar el proyecto utilizamos jupyter notebook con las libreria que se detalla a continuación:
1. Pandas y NumPy para manipulación y limpieza de datos.
2. Matplotlib, seaborn y Plotly para realizar visualizaciones.
3. Scikit-learn e imbalanced-learn para realizar, evaluar y perfeccionar modelos de machine learning.

**Resultados**

Luego del trabajo realizado las métricas finales obtenidas fueron las siguientes:

             precision    recall  f1-score   support
       0       0.84      0.86      0.85     16187
       1       0.86      0.83      0.84     16190
       2       0.99      1.00      0.99     16205

    accuracy                           0.90     48582
    macro avg      0.90      0.90      0.90     48582
    weighted avg   0.90      0.90      0.90     48582

Para ver el trabajo detalladamente ingresar al siguiente link:https://drive.google.com/file/d/1O9zI0Wpwpre3pyoq39UiDLN4dI3ZrMNK/view?usp=sharing
