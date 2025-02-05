  {
   "attachments": {},
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "<img src=\"images/maintenance.jpg\" width=\"1300\"  height = \"250\" style=\"margin:0 auto;clear:both\">\n",
    "\n",
    "***Victor Hugo Cruz Espinoza, proyecto final***\n",
    "___\n",
    "\n",
    "# **GENERACIÓN DE MODELOS DE MACHINE LEARNING PARA APLICACIONES DE PREDICCIÓN DE ESTADOS DE FALLA EN TRANSFORMADORES DE DISTRIBUCIÓN** \n",
    "___"
   ]
  }
# Generación de modelos de machine learning para aplicaciones de predicción de estados de falla en transformadores de distribución

El objetivo del presente trabajo consiste en implementar dos modelos de machine learning capaces de predecir el estado de falla de transformadores de distribución en función de dos clases: Clase 0 transformador en buen estado y clase 1 transformador quemado; predecir el estado de alarma del indicador de aceite magnético (MOG), en función de dos clases: Clase 0 estado normal y clase 1 estado de alarma. La detección temprana de estos estados de falla de los transformadores evitarán la salida de operación de estos equipos, garantizando la intervención oportuna.  

Para el desarrollo de los modelos se optó por usar los algortimos de clasificación de scikit-learn: Logistic regresion, decission tree, random forest, SVM y K-NN. El modelo final seleccionado corresponde al algoritmo random forest.

El primer conjunto de datos empleados en el proyecto fue recopilado por el operador de la red (Compañía energética de Occidente) en el departamento del Cauca (Colombia), en colaboración con la Universidad del Cauca y la Universidad del Valle. Este dataset es abierto para su uso en proyectos de Ciencia de Datos en el siguiente enlace: https://www.sciencedirect.com/science/article/pii/S2352340921007368?via%3Dihub

El segundo conjunto de datos pertenece a la plataforma kaggle en el siguiente enlace: https://www.kaggle.com/datasets/sreshta140/ai-transformer-monitoring 

______

El trabajo corresponde al módulo final del diplomado en ESTADÍSTICA APLICADA A LA TOMA DE DECISIONES de la Universidad Mayor de San Simón 

Lugar: Cochabamba (Bolivia)

Autor: Victor H. Cruz.

Correo: victor.vhce.94@gmail.com

Reconocimiento intelecual: El presente trabajo toma como base objetiva y metodológica, la investigación de Alvarez Q, Lozano M, & Bravo M (2022). *Metodología para el mantenimiento predictivo de transformadores de distribución basada en aprendizaje automático*. Mensión al trabajo del usuario AFROZ en su trabajo denominado *transformer fault prediction with 99% auc*. 
