# Sistema Inteligente de Reconocimiento de Vida Salvaje

## Descripción

Este proyecto implementa un modelo de aprendizaje profundo basado en ResNet50 para clasificar imágenes en tres categorías: gatos, perros y animales salvajes. Utiliza el dataset Animal Faces (AFHQ) para entrenar y validar el modelo, y permite evaluar nuevas imágenes externas para comprobar su capacidad de reconocimiento.

## Contenido del Notebook

- Descarga y preparación del dataset Animal Faces.
- Definición de generadores de imágenes con aumentos y preprocesamiento.
- Construcción y entrenamiento del modelo con transferencia de aprendizaje.
- Evaluación del modelo con métricas de precisión, recall y F1-score.
- Pruebas en imágenes reales para validar el desempeño fuera del dataset.

## Requisitos

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib (opcional, para visualizaciones)
- Google Colab (opcional, recomendado para facilitar la ejecución)

## Cómo usarlo

1. Clona o descarga el notebook.
2. Ejecuta paso a paso para descargar el dataset y preparar los datos.
3. Entrena el modelo (puedes modificar el número de epochs).
4. Evalúa el modelo y realiza pruebas con imágenes externas.
5. Guarda el modelo entrenado para uso futuro.

## Futuras mejoras

- Ampliar el dataset con más clases de animales.
- Implementar técnicas de afinamiento (fine-tuning) avanzadas.
- Añadir interfaz gráfica para facilitar el uso.
- Experimentar con otras arquitecturas de redes neuronales.
