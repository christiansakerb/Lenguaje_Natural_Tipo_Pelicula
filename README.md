# Clasificación de Géneros de Películas Usando Procesamiento de Lenguaje Natural (NLP)

## Descripción del Proyecto

Este repositorio contiene un proyecto enfocado en la clasificación de géneros de películas basándose únicamente en sus descripciones. Cada película puede pertenecer a varios géneros, y utilizamos técnicas de **Procesamiento de Lenguaje Natural (NLP)** en Python para realizar esta clasificación multietiqueta. El proyecto implica la limpieza, el procesamiento y el análisis de los textos para extraer características significativas y, finalmente, predecir los géneros mediante una red neuronal.

![image](https://github.com/user-attachments/assets/c8827fa2-6b0d-4953-97f6-d13930a7441d)


## Características Clave

- **Preprocesamiento de Datos**: 
  - Limpieza de texto, incluyendo la eliminación de stopwords y lematización.
  - Vectorización de palabras usando varias técnicas (TF-IDF, Bag of Words).
  - Análisis de las palabras más comunes en los diferentes géneros.
  
- **Modelado**:
  - Resolución de un problema de clasificación multietiqueta mediante una **red neuronal** implementada con la librería **TensorFlow**.
  - La variable objetivo (los géneros de las películas) se codificó como dummies para el entrenamiento.
  - La red neuronal se entrena utilizando un enfoque de **aprendizaje supervisado**, con división de los datos en entrenamiento y prueba.
  
- **Evaluación del Desempeño**:
  - Se utilizan varias métricas de evaluación, como el **AUC** (Área Bajo la Curva) y la **precisión**, para medir el rendimiento del modelo.
  
## Flujo de Trabajo

1. **Limpieza de Datos**:
   - Tokenización, lematización y eliminación de stopwords para preprocesar las descripciones de las películas.
   
2. **Extracción de Características**:
   - Conversión del texto limpio en vectores mediante técnicas de vectorización de palabras.
   
3. **Entrenamiento del Modelo**:
   - Entrenamiento supervisado utilizando una red neuronal diseñada para clasificación multietiqueta.
   - El modelo predice géneros para cada película en función de la descripción, aprovechando la potencia de los embeddings de palabras.

4. **Evaluación**:
   - Se calculan métricas como el AUC y la precisión para evaluar el rendimiento del modelo.

## Librerías Utilizadas

- Python
- TensorFlow
- Scikit-learn
- NLTK (Natural Language Toolkit)
- Pandas
- NumPy

## Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/yourusername/movie-genre-classification.git

2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt

El archivo `requirements.txt` incluye todas las librerías necesarias para ejecutar el proyecto, como TensorFlow, Scikit-learn, NLTK, Pandas, y NumPy. Estas herramientas son clave para realizar el procesamiento de lenguaje natural (NLP), la vectorización de palabras y la construcción del modelo de red neuronal para la clasificación de géneros de películas.

