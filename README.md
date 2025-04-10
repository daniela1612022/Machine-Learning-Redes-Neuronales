# Radiografías y Redes Neuronales 🧠📸

Este proyecto implementa una Red Neuronal Convolucional (CNN) utilizando Keras y TensorFlow para clasificar radiografías de tórax en dos categorías: **normales** y **neumonía**.

## 📂 Estructura del proyecto

- `Radiografias_Redes_Neuronales.ipynb`: Notebook principal que contiene todo el flujo de trabajo, desde la carga de datos hasta la evaluación del modelo.
- Dataset esperado: Estructura similar a la del conjunto de datos de radiografías de Kaggle o similares, con carpetas `/train`, `/val`, y `/test` divididas en clases.

## 🚀 Tecnologías utilizadas

- Python 🐍
- TensorFlow y Keras
- Matplotlib y NumPy
- Google Colab (opcional para entrenamiento con GPU)

## 🧪 ¿Qué hace el modelo?

El modelo:
- Carga y preprocesa imágenes.
- Aplica técnicas de aumento de datos para mejorar la generalización.
- Entrena una CNN con varias capas convolucionales, de pooling y densas.
- Evalúa el desempeño en datos de prueba.
- Muestra gráficamente la evolución de la precisión y pérdida.

## 🏁 Cómo usar

1. Asegúrate de tener los siguientes paquetes instalados:
   ```bash
   pip install tensorflow matplotlib numpy
