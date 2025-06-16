# 🎬 Análisis de Sentimiento en Reseñas de Películas (IMDB)

> Proyecto final de Procesamiento de Lenguaje Natural (NLP) — Aplicación sobre datos reales de reseñas de películas.

---

## 📌 Objetivo

Aplicar técnicas de NLP y modelos de clasificación para **analizar reseñas de películas** y predecir si su contenido es **positivo o negativo**. El trabajo incluye limpieza, análisis lingüístico, extracción de entidades, visualización y entrenamiento de modelos.

---

## 🧰 Tecnologías y herramientas utilizadas

- 🧠 **spaCy** – Tokenización, lematización, POS-tagging, NER.
- 🧹 **TextBlob** – Análisis de polaridad y subjetividad.
- 🔢 **TF-IDF / Bag of Words** – Vectorización textual.
- 🤖 **Scikit-learn** – Modelos de clasificación (Logistic Regression).
- 🔬 **TensorFlow / Keras** – Red neuronal simple.
- 📊 **Seaborn / Matplotlib / WordCloud** – Visualización de datos.

---

## 🔍 Principales pasos del análisis

- ✅ Limpieza y preprocesamiento del texto (lemmatización, stopwords, puntuación).
- ✅ Análisis gramatical y entidades nombradas (NER).
- ✅ WordCloud para reseñas positivas y negativas.
- ✅ Vectorización con TF-IDF.
- ✅ Análisis de polaridad y subjetividad.
- ✅ Clasificación con regresión logística.
- ✅ Red neuronal para clasificación binaria.

---

## 🧪 Resultados obtenidos

- 📈 **Precisión con Logistic Regression:** rendimiento aceptable en clasificación binaria.
- 🧠 **Precisión con red neuronal simple:** ~77% en conjunto de prueba.
- 📉 Análisis visual de pérdida y precisión durante el entrenamiento.
- 🧾 Análisis interpretativo del lenguaje en función del sentimiento.

---

## 📂 Dataset

El dataset utilizado es **IMDBDataset.csv**, el cual contiene reseñas clasificadas como `positive` o `negative`. Fue cargado, muestreado y limpiado para garantizar balance y calidad en los datos de entrada.

---

## 📚 Estructura del proyecto

```plaintext
📁 movies_reviews/
│
├── 📓 DatasetAgustin.ipynb
├── 📄 README.md

María Mercedes Agustin
