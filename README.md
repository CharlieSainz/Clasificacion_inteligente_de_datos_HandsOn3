# Clasificacion_inteligente_de_datos_HandsOn3
Assignments de la materia de Clasificacion inteligente de datos 

# Clasificador K-Means
Este proyecto es un tutorial en Python sobre la técnica de clasificación K-Means, implementada con la librería scikit-learn.  
El objetivo es comprender cómo funciona este método de agrupamiento no supervisado y cómo aplicarlo paso a paso en un conjunto de datos real.

---

## Contenido
- Fundamentos teóricos del algoritmo K-Means  
- Modelo matemático  
- Descripción de librerías y funciones utilizadas  
- Pipeline con las siguientes etapas:
  - Preprocesamiento  
  - Prediction  
  - Model Evaluation (Matriz de confusión y Accuracy)  

---

## Descripción general
K-Means es un algoritmo de agrupamiento no supervisado que busca dividir los datos en **k grupos (clusters)** según su similitud.  
A diferencia de los clasificadores supervisados, no utiliza etiquetas conocidas durante el entrenamiento.  
El algoritmo asigna cada punto al centroide más cercano y recalcula los centroides hasta que las asignaciones no cambian.

En este trabajo se usa el **dataset Iris**, el cual contiene tres tipos de flores y cuatro variables (largo y ancho de pétalos y sépalos).  
Se entrena un modelo con `k = 3` para identificar los grupos de manera automática y se compara con las clases reales.

---

## Requisitos
Para ejecutar el notebook se necesitan las siguientes librerías:
```bash
pip install scikit-learn matplotlib seaborn numpy pandas
