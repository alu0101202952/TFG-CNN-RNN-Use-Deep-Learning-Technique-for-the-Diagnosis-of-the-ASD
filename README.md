# TFG-CNN-RNN-Use-Deep-Learning-techniques-for-the-diagnosis-of-ASD

## Uso de técnicas de Deep Learning para el diagnóstico del TEA
### Andrea Calero Caro
### Trabajo de fin de grado
### Grado Ingeniería Informática
### Universidad de La Laguna

-------------------------------------------------------------------------
#### El objetivo de este proyecto ha sido desarrollar un algoritmo mediante “aprendizaje supervisado” que, a partir de los datos obtenidos de imágenes sea capaz de clasificar una serie de individuos en los grupos con o sin TEA, (Trastorno del Espectro Autista) con un nivel de confiabilidad aceptable. Cuyo fin es proporcionar una herramienta que ayude a los facultativos del sector sanitario en el diagnóstico precoz de este trastorno. Se emplearán herramientas como Jupyter Notebook, Anaconda, TensorFlow, entre otras. Además, se utilizarán técnicas de Data Mining para la explotación de los datos en Python. Todo ello alojado en un cuaderno de Jupyter Notebook.

#### Algoritmos empleados:
- Red neuronal convolucional (CNN)
- Red neuronal recurrente (LSTM)

-------------------------------------------------------------------------

#### Orden de ejecución del programa:
1. Ejecutar fichero "**analisisEstadistico**" (Contiene el análisis y visualización de los datos a modo estadístico)
2. Ejecutar fichero "**borrarAll**" (Contiene una función para borrar la carpeta All y evitar hacerlo de forma manual)
3. Ejecutar fichero "**entrenamiento**" (Contiene el entrenamiento con ambos modelos: CNN y LSTM)
4. Ejecutar fichero "**limpiarCodificar**" (Contiene la función de limpieza y codificación de los datos antes de pasarlos al análisis, clasificar y entrenar)
5. Ejecutar fichero "**clasificarDatos**" (Contiene la función que crea los datasets que serán para la parte de entrenamiento y de prueba, funciona pero se pretende que en un futuro sea una aplicación nativa que funcione como [Link]([https://ejemplo.com/](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html), "*train_test_split*") de la librería scikit-learn)
