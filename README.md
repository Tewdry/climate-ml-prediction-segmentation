# 🌦️ Análisis Predictivo y Segmentación Climática usando Machine Learning

## 📌 Descripción del Proyecto
Este proyecto desarrolla un **pipeline completo de Data Science aplicado a datos climáticos de Australia**, con el objetivo de **predecir eventos de lluvia**, **estimar la cantidad de precipitación** y **descubrir patrones climáticos** mediante técnicas de *Machine Learning supervisado y no supervisado*.

El enfoque simula un escenario real de análisis de datos, integrando limpieza, exploración, modelado, evaluación y visualización de resultados.

---

## 🎯 Objetivos
- Predecir la ocurrencia de lluvia en un día determinado (*clasificación*)
- Estimar la cantidad de precipitación (*regresión*)
- Identificar patrones climáticos mediante técnicas de *clustering*
- Reducir la dimensionalidad de los datos para visualización y análisis

---

## 📊 Dataset
- **Origen:** Dataset meteorológico de Australia
- **Tipo:** Datos estructurados y multivariables
- **Variables:**  
  Temperatura, humedad, presión atmosférica, velocidad del viento, precipitaciones, entre otras.
- **Variables objetivo:**
  - `RainTomorrow` (clasificación)
  - `Rainfall` (regresión)

---

## 🧹 Preprocesamiento de Datos
- Limpieza de datos y tratamiento de valores nulos
- Codificación de variables categóricas
- Escalado y normalización de variables numéricas
- Selección de características relevantes

---

## 🔍 Análisis Exploratorio de Datos (EDA)
- Análisis estadístico descriptivo
- Estudio de correlaciones entre variables
- Visualización de distribuciones y patrones climáticos
- Identificación de variables con mayor impacto en la lluvia

---

## 🤖 Modelos de Machine Learning

### 📌 Aprendizaje Supervisado

#### Clasificación
- Regresión Logística
- Random Forest Classifier

**Métricas de evaluación:**
- Accuracy
- Precision
- Recall
- F1-score

#### Regresión
- Regresión Lineal
- Random Forest Regressor

**Métricas de evaluación:**
- RMSE
- Comparación entre modelos base y modelos avanzados

---

### 📌 Aprendizaje No Supervisado

#### Clustering
- K-Means
- Selección del número óptimo de clusters usando *Silhouette Score*
- Análisis e interpretación de segmentos climáticos

#### Reglas de Asociación
- Algoritmo Apriori
- Identificación de patrones frecuentes en variables climáticas

---

## 📉 Reducción de Dimensionalidad
- **PCA (Principal Component Analysis)**
- Análisis de varianza explicada
- Visualización de datos en espacios de menor dimensión
- Interpretación de componentes principales

---

## 📈 Resultados Principales
- Los modelos **Random Forest** mostraron el mejor desempeño tanto en clasificación como en regresión.
- Variables relacionadas con **humedad, temperatura y presión atmosférica** resultaron ser altamente influyentes.
- El clustering permitió identificar grupos climáticos con características diferenciadas.
- PCA facilitó la visualización de patrones complejos en los datos.

---

## ⚠️ Limitaciones
- No se consideró la dependencia temporal de los datos (series de tiempo).
- No se realizó optimización avanzada de hiperparámetros.
- El análisis se basa únicamente en datos históricos disponibles.

---

## 🚀 Próximos Pasos
- Incorporar modelos de **series temporales**
- Optimizar hiperparámetros con Grid Search o Random Search
- Integrar variables externas (estacionales o geográficas)
- Implementar el modelo como API o dashboard interactivo

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 👤 Autor
Proyecto desarrollado con fines de **portafolio profesional en Data Science**, demostrando habilidades en análisis de datos, machine learning y comunicación de resultados.
