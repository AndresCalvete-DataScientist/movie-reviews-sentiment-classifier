## 🎬 Clasificación de sentimientos en reseñas de películas con Machine Learning

### 📌 Introducción

Este proyecto forma parte del desarrollo de **Film Junky Union**, una comunidad para aficionados al cine clásico. El objetivo es entrenar un modelo de machine learning capaz de **detectar automáticamente críticas negativas en reseñas de películas**, utilizando datos de IMDB.  

El reto consiste en construir un clasificador de sentimientos que distinga entre reseñas positivas y negativas, alcanzando un **F1-score mínimo de 0.85**.

---

### 🎯 Objetivo

- Analizar un conjunto de datos de reseñas de películas.  
- Preprocesar el texto para su representación en modelos de machine learning.  
- Entrenar y comparar diferentes algoritmos de clasificación.  
- Evaluar el rendimiento de los modelos utilizando métricas como *accuracy*, *precision*, *recall* y *F1-score*.  
- Seleccionar el modelo final que cumpla con el umbral de desempeño (F1 ≥ 0.85).  

---

### 🧠 Habilidades técnicas demostradas

Este proyecto refleja competencias clave en **procesamiento de lenguaje natural (NLP)** y machine learning:

- **Análisis exploratorio de datos (EDA)**: revisión de distribución de reseñas y longitud de textos.  
- **Limpieza y transformación de texto**: tokenización, stopwords, lematización y vectorización (TF-IDF / Bag of Words).  
- **Modelado predictivo**: entrenamiento de clasificadores como *Logistic Regression* y *LightGBM*.
- **Deep Learning aplicado a NLP**: uso de **PyTorch** y la librería **Transformers** con **BERT**.  
- **Evaluación de modelos**: métricas como *accuracy*, *recall*, *precision* y *F1-score*.   
- **Documentación clara y reproducible**: flujo de trabajo modular en notebooks de Jupyter.  

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**  
- **pandas** y **NumPy**: manejo y transformación de datos.  
- **scikit-learn**: modelado y evaluación.  
- **NLTK / spaCy**: preprocesamiento de texto.  
- **matplotlib / seaborn**: visualización de datos y métricas.  
- **tqdm**: seguimiento de procesos iterativos.  

---

### ✅ Resultados y conclusiones

- Se entrenaron y compararon varios modelos de clasificación de texto.  
- El modelo seleccionado fue el modelo 1 (NLTK, TF-IDF y LR) con un valor de **F1 de 0.88**, cumpliendo con el objetivo establecido.  
- Se recomendo evaluar el modelo 4 (BERT y LightGBM) haciendo uso de más datos en un ambiente con GPU.

---

### 📈 Posibles mejoras futuras

- Probar modelos avanzados como **redes neuronales**.  
- Implementar un pipeline con entrenamiento en GPU para **BERT**.  
- Desplegar el modelo en una API para clasificación en tiempo real.    

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
