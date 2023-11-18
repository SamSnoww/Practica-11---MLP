# Practica-11---MLP
# Redes Neuronales para Problemas XOR y Gaussian-Quantiles

Este repositorio contiene implementaciones en Python de dos modelos de redes neuronales: XOR Model y Gaussian-Quantiles Model.

## XOR Model

### Descripción
Utiliza una red neuronal de 3 capas para resolver el problema XOR. Utiliza métodos de retropropagación y descenso de gradiente para ajustar los parámetros.

### Entrenamiento
Los pesos y sesgos se inicializan aleatoriamente y se ajustan para minimizar el Error Cuadrático Medio (MSE). Se imprime el MSE durante el entrenamiento.

### Pruebas
El modelo entrenado se prueba con datos de entrada diferentes (`XOR_tst.csv`), y se muestra la salida predicha.

## Gaussian-Quantiles Model

### Descripción
Utiliza una red neuronal similar para el entrenamiento de datos generados con la función `make_gaussian_quantiles` de scikit-learn.

### Entrenamiento
Los pesos y sesgos se ajustan para minimizar el MSE. Se imprime el MSE durante el entrenamiento.

### Evaluación con Partículas Aleatorias
Se generan n partículas aleatorias y se evalúan con el modelo entrenado. Los resultados se imprimen en la consola.

## Requisitos

- Python 3.x
- Bibliotecas: NumPy, pandas, scikit-learn

## Configuración

Puedes ajustar la configuración del entrenamiento directamente en los scripts, como el número de épocas y la tasa de aprendizaje.
