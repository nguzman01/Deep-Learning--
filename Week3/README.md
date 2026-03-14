

# Objetivo
Implementación de Backpropagation y Funciones de Activación en Redes Neuronales

# Implementación 

Se desarrollaron tres arquitecturas.
- Perceptrón Simple: Sin capas ocultas (modelo lineal).
- Monocapa: Una capa oculta con 4 neuronas.
- Red Multicapa: Dos capas ocultas (4 neuronas cada una).
  
Luego se programó manualmente el flujo de Forward Propagation y el cálculo de gradientes para el Backpropagation, asegurando que el error se distribuya correctamente a través de la regla de la cadena.
  
# Que Activaciones se compararon

Se realizo una comparación de activaciones y se constrastaron las siguientes funciones:
- Sigmoide: Aplicada en modelos simples y como capa de salida.
- ReLU: Implementada en la red multicapa para mitigar el desvanecimiento del gradiente.


# Resultados Principales

El Perceptrón falló en el problema XOR (precisión del 25-50%), confirmando que no puede resolver problemas no lineales.
La Red Multicapa con ReLU fue la única que logró una precisión del 100%, demostrando una convergencia mucho más rápida y eficiente que el uso exclusivo de funciones sigmoides en capas profundas
-  Se logro una reducción del error (MSE) significativa en ambos modelos   tras 5000 épocas.
 
# Como se ejecuta 

1. Abrir el archivo terminado en '.ipynb' en Google Colab.
2. Ejecutar las celdas en orden secuencial para reproducir la grafica y las predicciones.
