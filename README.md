Guía de Ejecución - Algoritmo Genético TSP
Este repositorio contiene una implementación en Python para resolver el Problema del Agente Viajero (TSP) aplicado a las instancias gr17, gr21 y gr24 de TSPLIB.

Requisitos
El código requiere Python 3.x y las siguientes librerías:

numpy

matplotlib

Instrucciones para Google Colab
Abra un nuevo cuaderno en Google Colab.

Copie y pegue el código del archivo proporcionado en una celda de código.

Localice la sección final del script bajo el comentario CONFIGURACION.

Cambie el valor de la variable TARGET_INSTANCE por la instancia deseada: "gr17", "gr21" o "gr24".

Ejecute la celda (Ctrl + Enter).

Instrucciones para PC (Local)
Asegúrese de tener instaladas las dependencias: pip install numpy matplotlib

Guarde el código en un archivo con extensión .py (ejemplo: tsp_ga.py).

Ejecute el script desde la terminal: python tsp_ga.py

Parámetros del Algoritmo
El algoritmo está configurado por defecto con:

Población: 200 individuos.

Mutación: 20% (Inversión).

Cruce: Ordered Crossover (OX).

Generaciones: 1000.

Los resultados se mostrarán en la consola indicando la mejor ruta, la distancia obtenida y el margen de error respecto al óptimo teórico, seguido de una gráfica de convergencia.
