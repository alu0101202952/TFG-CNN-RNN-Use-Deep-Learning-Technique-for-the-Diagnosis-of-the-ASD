# TFG-CNN-RNN-Use-Deep-Learning-techniques-for-the-diagnosis-of-ASD

## Uso de técnicas de Deep Learning para el diagnóstico del TEA
### Andrea Calero Caro
### Trabajo de fin de grado
### Grado Ingeniería Informática
### Universidad de La Laguna

-------------------------------------------------------------------------
#### El objetivo de este proyecto ha sido desarrollar un algoritmo mediante “aprendizaje supervisado” que, a partir de los datos obtenidos de imágenes sea capaz de clasificar una serie de individuos en los grupos con o sin TEA, (Trastorno del Espectro Autista) con un nivel de confiabilidad aceptable. Cuyo fin es proporcionar una herramienta que ayude a los facultativos del sector sanitario en el diagnóstico precoz de este trastorno. Se emplearán herramientas como [Jupyter Notebook](https://jupyter.org/), Anaconda, TensorFlow, entre otras. Además, se utilizarán técnicas de Data Mining para la explotación de los datos en Python. Todo ello alojado en un cuaderno de Jupyter Notebook.

#### Algoritmos empleados:
- Red neuronal convolucional (CNN)
- Red neuronal recurrente (LSTM)

-------------------------------------------------------------------------

#### Ficheros añadidos al github:
- Cuaderno completo (.ipynb), dentro de la carpeta **Cuaderno**, con todos los ficheros.
- Ficheros de cada función por separado
  - "**analisisEstadistico**": (Contiene el análisis y visualización de los datos a modo estadístico)
  - "**borrarAll**": (Contiene una función para borrar la carpeta All y evitar hacerlo de forma manual)
  - "**entrenamiento**": (Contiene el entrenamiento con ambos modelos: CNN y LSTM)
  - "**limpiarCodificar**": (Contiene la función de limpieza y codificación de los datos antes de pasarlos al análisis, clasificar y entrenar)
  - "**clasificarDatos**": (Contiene la función que crea los datasets que serán para la parte de entrenamiento y de prueba, funciona pero se pretende que en un futuro sea una aplicación nativa que funcione como [train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) de la librería scikit-learn)

#### Orden de ejecución del programa, ficheros por separado:
1. Ejecutar fichero "**analisisEstadistico**"
2. Ejecutar fichero "**borrarAll**"
3. Ejecutar fichero "**entrenamiento**"
4. Ejecutar fichero "**limpiarCodificar**"
5. Ejecutar fichero "**clasificarDatos**"
