# Taller 5 Redes neuronales

### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---
## **Punto 1: Conjuntos de entrenamiento para una red neuronal que reconoce letras **
Archivo: [reconocLetras.ipynb](./reconocLetras.ipynb)

Descripción:  Este código realiza un análisis exploratorio y un modelo de clasificación utilizando el famoso dataset Iris. Primero, lee las descripciones del archivo iris.names para entender el contexto del conjunto de datos. Luego, analiza las estadísticas descriptivas del dataset y visualiza las distribuciones con un gráfico de pares coloreado por clase. Posteriormente, divide los datos en características y etiquetas, normaliza las clases con LabelEncoder y crea una red neuronal con Keras. La red, diseñada para clasificar las tres especies de iris, se entrena con un conjunto de datos dividido en entrenamiento y prueba, usando sparse_categorical_crossentropy como función de pérdida y el optimizador adam.

## **Punto 2: 100 imágenes de perros y 100 imágenes de gatos.**
Archivo:
Descripción: 
---


## **Punto 3:Diseño de una red neuronal **
Archivo: [Diseño_red_neuronal_Iris.ipynb](./Diseño_red_neuronal_Iris.ipynb)

Descripción: Este código implementa una red neuronal artificial (NNA) desde cero en Python. La red tiene una arquitectura fija con tres capas: dos ocultas y una de salida. Utiliza inicialización Xavier para los pesos y la función sigmoide como activación. El flujo principal incluye:
1. Propagación hacia adelante: Calcula las activaciones de cada capa para una entrada dada.
2. Cálculo de error: Compara la salida de la red con los valores deseados.
3. Retropropagación: Ajusta los pesos y sesgos para minimizar el error mediante el método de descenso de gradiente.
4. Entrenamiento: Itera sobre los datos de entrada y salida hasta que el error cuadrático medio sea aceptable o se alcance un número máximo de iteraciones. También ajusta dinámicamente la tasa de aprendizaje (learning rate).
El código incluye datos de entrenamiento que representan letras (A, E, I, O, U) en forma de matrices binarias y sus salidas deseadas codificadas. Finalmente, se entrena la red para reconocer estas entradas, mostrando la evolución del error durante el proceso y verificando la precisión de la salida entrenada.

### Notas adicionales:
Este repositorio contiene la resolución detallada de los puntos del taller 3 sobre algoritmos genéticos. Cada programa ha sido documentado con descripciones claras para facilitar su comprensión y replicación.
