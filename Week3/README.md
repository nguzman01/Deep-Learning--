

# Objetivo
Implementar una red neuronal con backpropagation para comparar el desempeño de las funciones de activación Sigmoid y ReLU en la reducción del error (MSE)
# Implementación 

 - Red neuronal con una capa oculta de 4 neuronas.
 - Algoritmo de Backpropagation, programado manualmente en Python/numpy.
 - Comparativa entre las funciones de activación Sigmoid y ReLu.
   
# Que Activaciones se compararon
En este caso, se evaluaron dos funciones distintas en la capa oculta.
 1. Sigmoid (Sigmoide) Una función que comprime los vectores entre 0 y 1, propensa al desvanecimiento     del gradiente.
 2. ReLu (Rectified Linear unit) una función lineal para valores positivos que aceleran el                entrenamiento al enviar la saturación de gradientes.


# Resultados Principales
-  Se evidencia que ReLu supero a Sigmoid en precisión, entregando valores finales mucho más cercanos a   0 y 1.
-  Se logro una reducción del error (MSE) significativa en ambos modelos   tras 5000 épocas.
 
# Como se ejecuta 

1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden secuencial para reproducir la grafica y las predicciones.
