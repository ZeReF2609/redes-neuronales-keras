# Redes Neuronales con Keras — 5 casos prácticos

Notebooks de introducción a redes neuronales con **TensorFlow / Keras**, aplicadas a problemas reales.

## `redes_neuronales_5_ejemplos.ipynb`
| # | Caso | Tipo de problema | Arquitectura |
|---|------|------------------|--------------|
| 1 | Diagnóstico de diabetes | Clasificación binaria | MLP Dense(16→8) + Dropout, salida sigmoid |
| 2 | Precio de viviendas | Regresión | MLP Dense(64→32→16) + BatchNorm, salida lineal |
| 3 | Clasificación de prendas (Fashion-MNIST) | Clasificación de imágenes | CNN Conv2D(32/64) + MaxPool, softmax 10 clases |
| 4 | Detección de spam | NLP | Embedding + GlobalAveragePooling + Dense |
| 5 | Predicción de ventas | Series de tiempo | LSTM(50→25) con ventanas de 30 días |

## `ma1-celsius.ipynb`
Primer modelo: una red `Sequential` de una neurona que **aprende la fórmula Celsius → Fahrenheit**
a partir de ejemplos, para entender pesos, sesgo, función de pérdida y entrenamiento.

## Tecnologías
Python · TensorFlow · Keras · NumPy · pandas · matplotlib · scikit-learn · Jupyter / Google Colab

## Ejecutar
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```

Trabajo académico — Universidad Privada del Norte. Autor: [Wilder Rojas](https://github.com/ZeReF2609)
