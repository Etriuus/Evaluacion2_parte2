# Evaluacion2_parte2

#Integrantes:
Matias Cartes
Daniel ValdebenitoS

# 📊 Evaluación 2 - Parte 2: Modelos de Clasificación

**Autores:**  
- Daniel Valdebenito  
- Matías Cartes  

**Asignatura:** Inteligencia Artificial  
**Universidad del Bío-Bío – Sede Concepción**  
**Fecha:** Junio 2025

---

## 📌 Descripción

Este repositorio contiene el desarrollo del modelo de clasificación binaria para predecir la deserción de clientes (churn) en un servicio de suscripción, como parte de la Evaluación 2 de la asignatura de Inteligencia Artificial.

El objetivo principal es identificar a los clientes con mayor probabilidad de abandonar el servicio, permitiendo a la empresa tomar acciones preventivas.

---

## 🧠 Modelos evaluados

- Regresión Logística  
- Árbol de Decisión  
- Random Forest  
- Naive Bayes

---

## 📈 Resultados clave

| Modelo              | Precision | Recall | F1-score |
|---------------------|-----------|--------|----------|
| Regresión Logística | 0.710     | 0.737  | 0.723    |
| Árbol de Decisión   | 0.768     | 0.764  | 0.766    |
| Random Forest       | 0.753     | 0.784  | 0.768    |
| **Naive Bayes**     | 0.660     | **0.972** | **0.786** |

---

## 🏁 Conclusión

El modelo **Naive Bayes** fue el más efectivo para detectar casos de abandono, alcanzando un recall de **97.2%** y el mejor F1-score.  
Aunque otros modelos fueron más precisos, Naive Bayes es preferido porque permite anticipar mejor el churn, que es el objetivo principal del negocio.

---

## ⚙️ Requisitos de software

- Python 3.9  
- numpy 2.0.2  
- pandas 2.2.2  
- matplotlib 3.10.0  
- seaborn 0.13.2  
- scikit-learn 1.6.1  

---
https://raw.githubusercontent.com/JaznaLaProfe/InteligenciaArtificial/main/data/dataset_churn_2025.csv
https://github.com/Etriuus/Evaluacion2_parte2/blob/main/Daniel_Matias_T3.ipynb
https://colab.research.google.com/drive/1Zk0ZTI8-5-GfVRFQfBIzL1AqY-mRZHBh?usp=sharing#scrollTo=48lMRPZu4RSM
