# Sistema-Inteligente-de-Reconocimiento-de-Vida-Salvaje
Sistema Inteligente de Reconocimiento de Vida Salvaje

Este proyecto implementa un sistema de clasificación automática de imágenes de animales (gatos, perros y vida salvaje) utilizando técnicas de aprendizaje profundo y transferencia de aprendizaje con el modelo ResNet50. La solución está orientada a su potencial aplicación en tareas de conservación, monitoreo ambiental y automatización de análisis visual.

📌 Objetivo
Desarrollar un modelo capaz de identificar la clase de un animal en una imagen, diferenciando entre:

Gato (doméstico)

Perro (doméstico)

Salvaje (vida silvestre)

🧠 Enfoque técnico
Modelo base: ResNet50 preentrenada en ImageNet

Técnica: Transferencia de aprendizaje con fine-tuning

Dataset: AFHQ (Animal Faces-HQ)

Frameworks: PyTorch, torchvision

Entrenamiento: 80% entrenamiento, 10% validación, 10% test

Evaluación: Accuracy, Recall, Precision, F1-Score, matriz de confusión

📈 Resultados
Validación: Alta precisión (99.87%)

Test: Bajo rendimiento (F1 ~34%) debido a sobreajuste

Diagnóstico: Falta de generalización y confusión entre clases similares

⚠️ Limitaciones
El modelo presenta sobreajuste y una débil capacidad de generalización en datos no vistos. Se requieren mejoras en la diversidad del dataset y ajustes en el entrenamiento para su despliegue en entornos reales.

🔭 Líneas futuras
Aumento y diversificación de datos

Pruebas con modelos alternativos (e.g., EfficientNet, ViT)

Técnicas de ensemble

Clasificación jerárquica

Optimización del fine-tuning y regularización

🚀 Aplicaciones potenciales
Conservación de fauna

Sistemas de vigilancia ambiental

Curaduría automática de contenido visual

Monitoreo remoto mediante cámaras trampa

