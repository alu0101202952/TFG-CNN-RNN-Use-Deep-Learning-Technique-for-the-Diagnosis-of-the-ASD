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

### ESTRUCTURA DEL GITHUB

#### Contenido del cuaderno añadido al github:
- Cuaderno completo (.ipynb), dentro de la carpeta **Cuaderno**, con las funciones:
  - "**analisisEstadistico()**": (Contiene el análisis y visualización de los datos a modo estadístico)
  - "**borrarAll()**": (Contiene una función para borrar la carpeta All y evitar hacerlo de forma manual)
  - "**crearrAll()**": (Contiene una función para crear la carpeta All y evitar hacerlo de forma manual)
  - "**tratamientoDatos()**": (Contiene una función para separar los datos X de los Y y realizar el protocolo de ventana deslizante)
  - "**dividirSecuencias()**": (Contiene una función para realizar el algoritmo de organización de ventana deslizante y sacar la X e Y con la que se concatenará de cada fichero para su posterior entrenamiento)
  - "**OneHotEncoderFunction()**": (Contiene la codificación que se aplicará con el método One-Hot Encoding a la columna Y (TEA, no TEA))
  - "**entrenamiento()**": (Contiene el entrenamiento con ambos modelos: CNN y LSTM)
  - "**limpiarCodificar()**": (Contiene la función de limpieza y codificación de los datos antes de pasarlos al análisis, clasificar y entrenar)
  - "**clasificarDatos()**": (Contiene la función que crea los datasets que serán para la parte de entrenamiento y de prueba, funciona pero se pretende que en un futuro sea una aplicación nativa que funcione como [train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) de la librería scikit-learn)

-------------------------------------------------------------------------

### EJECUCIÓN

#### Primera vez de ejecución del programa:
1. Ejecutar parte "**analisisEstadistico**"
2. Ejecutar parte "**borrarAll**"
3. Ejecutar parte "**crearAll**"
4. Ejecutar parte "**dividirSecuencias** y **tratamientoDatos**"
5. Ejecutar parte "**OneHotEncoderFunction**
6. Ejecutar parte "**limpiarCodificar**"
7. Ejecutar parte "**entrenamiento**"
8. Ejecutar parte "**clasificarDatos**"

#### Siguientes veces de ejecución del programa: Si se ejecutó ya por primera vez y se quiere cambiar la parametrización del entrenamiento(es decir, el optimizador: adam,nadam,adamax, el tipo de función de pérdida: tf.keras.losses.CategoricalCrossentropy(), o se quiere cambiar otro valor por ejemplo del tamaño del lote), su ejecución es la siguiente gracias al menú que se ejecuta tras llamar a la función **clasificarDatos()**:
1. Se cambian los parámetros en la función "**entrenamiento**"
2. Ejecutar Ejecutar parte "**entrenamiento**"
3. Ejecutar parte "**clasificarDatos**"

**NOTA: PARA QUE ESTO SEA POSIBLE ES RECOMENDABLE SALIR SIEMPRE DEL MENÚ, PARA ELLO ELEGIR LA OPCIÓN "0" SI SE QUIERE BORRAR EL FICHERO DE ENTRENAMIENTO Y "1" SI SE QUIERE MANTENER, CON ELLO SALE DEL PROGRAMA**
