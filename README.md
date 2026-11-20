![Banner](banner.png)

# Predicción de la satisfacción del pasajero basada en la calidad del servicio en la aerolínea

## Integrantes
- Cristian Mauricio Tello Diaz

## Objetivo
Predecir si un pasajero queda satisfecho o neutral/insatisfecho con la aerolínea a partir de 21 variables (perfil del cliente, datos del vuelo y calificaciones del servicio), comparando modelos supervisados (árbol de decisión, random forest, SVM y redes neuronales) y explorando la estructura de los datos con aprendizaje no supervisado (PCA, K-Means y DBSCAN).

## Dataset
- Enlace: **(https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k)**
- 129.880 pasajeros, 21 variables de entrada y la variable objetivo `satisfaction`.

## Resultados principales
| Modelo | Accuracy (test) |
|---|---|
| Random Forest (150 árboles) | 96,12 % |
| Red neuronal 10 capas | 95,41 % |
| Árbol de decisión (profundidad 14) | 95,34 % |
| Red neuronal 6 capas | 95,32 % |
| Red neuronal 3 capas | 94,99 % |
| SVM (kernel rbf) | 94,40 % |

K-Means (k = 2) alcanzó una pureza de 76,1 % frente a la satisfacción real.

## Contenido del repositorio
- `Proyecto_IA.ipynb`: notebook acumulativo (partes 1, 2 y 3).
- `Diapositivas_Proyecto_IA.pdf`: resumen del semestre.
- `banner.png`: banner del proyecto.
