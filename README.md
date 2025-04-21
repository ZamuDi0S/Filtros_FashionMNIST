# 🔍 Clasificación de imágenes con filtros y PCA usando Fashion-MNIST

Este proyecto aplica técnicas de procesamiento de imágenes y reducción de dimensionalidad para analizar y clasificar imágenes del dataset **Fashion-MNIST**.

## 🧠 Técnicas utilizadas

- **Filtros aplicados:**
  - Filtro de bordes (Sobel)
  - Ecualización del histograma
  - Wavelets (PyWavelets - Haar)

- **Reducción de dimensionalidad:**
  - PCA (Análisis de Componentes Principales)

- **Clasificación:**
  - SVM (Máquinas de Vectores de Soporte)

## 📦 Librerías principales

- `numpy`, `matplotlib`, `cv2`, `pywt`, `PIL`
- `scikit-learn` para PCA y clasificación
- `tensorflow.keras.datasets` para cargar Fashion-MNIST

## 🚀 Cómo ejecutar

1. Abre el notebook en Google Colab o tu entorno local.
2. Ejecuta todas las celdas. No necesitas descargar datasets adicionales.
3. Observa los efectos de los filtros y el rendimiento del clasificador.

## 📁 Dataset

Se utiliza el dataset **Fashion-MNIST**, que viene integrado en Keras, por lo que no necesitas descargarlo manualmente.

## 📊 Resultados esperados

- Visualización de filtros aplicados a imágenes de ropa.
- Gráfica de componentes principales.
- Clasificación con SVM y reporte de precisión.

---

> Este proyecto fue desarrollado como parte del Diplomado de Ciencia de Datos - Primavera 2025.
