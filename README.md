# Detección de Caras Reales vs. Falsas utilizando Aprendizaje Automático

Este repositorio contiene el código y los resultados de un estudio que aborda el desafío de desarrollar un modelo de aprendizaje automático capaz de distinguir entre caras reales y falsas. El estudio utiliza diversas técnicas, incluyendo el aumento de datos, la regularización y el aprendizaje por transferencia, y se llevó a cabo utilizando Python.

## Resumen del Estudio

Este estudio aborda el desafío de desarrollar un modelo de aprendizaje automático capaz de distinguir entre caras reales y falsas. La experimentación se llevó a cabo utilizando Python y abarcó diversas técnicas, incluyendo el aumento de datos, la regularización y el aprendizaje por transferencia. Además, se empleó la plataforma Weight&Biases para visualizar los resultados en tiempo real y facilitar el monitoreo del proceso de entrenamiento.

Los resultados más destacados de esta investigación muestran un impresionante nivel de precisión con un accuracy del 81% en el conjunto de prueba. Además, se obtuvo una sólida curva ROC con un área bajo la curva (AUC) de 0.91. Sin embargo, se observó que el principal desafío reside en la tendencia de la red a clasificar erróneamente caras falsas como reales. En resumen, este estudio representa un esfuerzo significativo que ha logrado desarrollar un modelo efectivo para abordar la problemática de distinguir entre caras reales y falsas.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

- `Proyecto.ipynb`: Un archivo Jupyter Notebook que contiene el código del entrenamiento y la validación del modelo.

- `Memoria.pdf`: Un archivo PDF que contiene el artículo científico de la explicación del proyecto.

- `real_and_fake_face/`: Una carpeta que contiene los datos utilizados para entrenar el modelo.

- `modelos/`: Una carpeta que contiene dos modelos de reconocimiento de caras:
    - `facenet_128.pth`: Modelo para imágenes de 128x128 píxeles.
    - `face_recognition160.pth`: Modelo para imágenes de 160x160 píxeles.

## Instrucciones de Uso

Para replicar los resultados o utilizar el modelo entrenado, sigue estos pasos:

1. Clona este repositorio en tu sistema local.
2. Abre el archivo `proyecto.ipynb` en un entorno de Jupyter Notebook.
3. Sigue las instrucciones y ejecuta las celdas en orden para entrenar y validar el modelo.
4. Puedes utilizar los modelos pre-entrenados en la carpeta `modelos/` para realizar inferencias en tus propias imágenes.

## Dependencias

Asegúrate de tener instaladas las siguientes bibliotecas de Python antes de ejecutar el código:

- NumPy
- TensorFlow
- scikit-learn
- Matplotlib
- Weight&Biases (WandB)
- PyTorch

## Créditos

Este estudio fue realizado por Susana Suárez Mendoza y Mara Pareja del Pino como parte de la realización de una práctica de la asignatura Aprendizaje Automático II impartida en el grado de Ciencia e Ingeniería de Datos de la universidad de Las Palmas de Gran Canaria. 

- [Mara Pareja](https://github.com/marapareja17)
- [Susana Suárez](https://github.com/susanasrez)
