
# Objetivo
Implementar y validar una red neuronal basica 

# Implementacion 
* Entradas(X) y pesos (W): Definición de vectores para la toma de deciciones.
* Sesgos (bias): Ajuste de sensibilidad del modelo.
* Puntaje Z: Calculo de la suma ponderada ($z = \sum (x_i \cdot w_i) + b$).
* Funcion de Activación: Clasificación binaria (0 o 1) basadaen el umbral.

# Pruebas Realizadas
Se realizaron 4 casos de prueba con combinaciones binarias [1,1], [1,0],[0,1],[0,0], y asi observar como varia el puntaje z y la lasificaión final segun los pesos de asignados.

# Resultados Principales 
Se pude ver que el modelo puede clasificar correctamente las entradas, demostrando que la neurona se activa cuando el  puntaje z es igual o superior al del umbral establecido. En las pruebas se evidencio en caso 1 y2  que un peso alto (0.7) es suficiente para alcanzar el umbral incluso si una de las entradas es 0.

# Cómo Ejecutar

1. abrir el archivo terninado en '.ipynb' en Google Colad.
2. Ejecutar ( Entorno de ejecución > Ejecutar Todas) 
