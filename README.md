# # Clasificación de Supervivencia en el Titanic con K-Nearest Neighbors (KNN)

---

Este proyecto aplica Machine Learning para predecir la supervivencia de pasajeros del Titanic, utilizando el dataset público de Kaggle.  
El objetivo es clasificar si un pasajero sobrevivió(1) o no(0) en función de sus características, empleando el algoritmo **K-Nearest Neighbors (k-NN)**.

---

# Preparación de los Datos
Durante el preprocesamiento se realizaron las siguientes transformaciones:

- Conversión de variables:
  - `Sex`: male → 0, female → 1  
  - `Embarked`: S → 0, C → 1, Q → 2  
- Eliminación de columnas con demasiados valores faltantes (`Cabin`).  
- Imputación de datos faltantes:
  - `Age`: reemplazado por la **media**.  
  - `Embarked`: reemplazado por **moda**.  
- Eliminación de valores atípicos en `Age` (edades ≤ 0).  
- Eliminación de filas duplicadas(aunque no habia ninguna pero por si acaso).

---

# Variables Utilizadas X:
- `Sex`  
- `Pclass`  
- `Age`  

# Variable Utilizada y:
- `Survived` (0 = No sobrevivió, 1 = Sobrevivió).  

---

Captura del podio obtenido:
<img width="1089" height="588" alt="Captura" src="https://github.com/user-attachments/assets/2f2dc408-9a9f-4692-95d9-38435524aed1" />
