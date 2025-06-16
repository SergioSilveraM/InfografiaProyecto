# Optimization of Debt Collection Management in a Colombian BPO: Integration of Machine Learning Models and Fuzzy Inference for Client Segmentation and Prioritization

![Expert System](https://raw.githubusercontent.com/SergioSilveraM/InfografiaProyecto/main/images/Expert_Sistem.png)

## Author
**Sergio Silvera Murcia**
* **LinkedIn:** [linkedin.com/in/sergio-silvera-murcia](https://www.linkedin.com/in/sergio-silvera-murcia/)
* **GitHub:** [@SergioSilveraM](https://github.com/SergioSilveraM)

---

## 🌐 English Version

### ✨ Interactive Infographic

For a complete and visual exploration of this project, we invite you to view the **interactive web infographic**: 
**[➡️ Click here to see the presentation](https://sergiosilveram.github.io/InfografiaProyecto/)**

### 🚀 Project Summary

This repository contains the source code for the interactive infographic and visual materials for the master's degree thesis project in Data Analytics.

The project develops a **hybrid expert system** that integrates the predictive power of **machine learning (XGBoost)** with the ability of **fuzzy logic** to handle uncertainty. The goal is to optimize collection management in a BPO through intelligent and precise risk segmentation, allowing for resource prioritization and the design of personalized collection strategies.

### 🎯 The Problem

Traditional collection management in BPOs often lacks precise risk segmentation, resulting in:
* **Inefficient resource allocation**.
* Low portfolio recovery rates.
* Lack of personalized strategies for debtors.

This project addresses the following question:
> *How can a BPO in Colombia optimize the management and recovery of its overdue portfolio through an intelligent system that combines machine learning and fuzzy logic techniques to segment clients and design personalized collection strategies, considering the characteristics of the available data?*

### 💡 The Proposed Solution

An expert system was designed and built following a robust multi-phase methodology:

1.  **Exploratory Data Analysis (EDA):** Deep understanding of the data, identifying imbalances and key features.
2.  **Model Benchmarking:** Multiple algorithms (Logistic Regression, Decision Trees, Random Forest, SVM, XGBoost) were rigorously compared using a **Nested Cross-Validation** scheme to ensure robustness.
3.  **Champion Selection:** The **XGBoost** model demonstrated the best overall performance, with an **AUC of 0.96** and an **F1-Score of 0.825**.
4.  **Fuzzy Inference System:** The probability output from XGBoost was integrated as input to a fuzzy logic system to translate numerical risk into **interpretable linguistic segments** (Very Low, Low, Medium, High, Critical Risk).
5.  **Explainability (XAI):** Techniques like **LIME** were used to ensure model interpretability, a crucial requirement in the financial sector.

### 🛠️ Technologies Used

* **Frontend:** HTML5, Tailwind CSS, JavaScript
* **Data Visualization:** Chart.js
* **Modeling (offline):** Python, Scikit-learn, XGBoost, Optuna, Skfuzzy
* **Hosting:** GitHub Pages

### 📂 Repository Structure

```bash
/
├── images/             # Contains all project images and graphics.
├── index.html          # The main interactive infographic file.
└── README.md           # The documentation you are reading.
```

### 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SergioSilveraM/InfografiaProyecto.git](https://github.com/SergioSilveraM/InfografiaProyecto.git)
    ```
2.  **Open the `index.html` file:**
    Navigate to the project folder and open the `index.html` file in your preferred web browser (Google Chrome, Firefox, etc.).

And you're all set! You can now explore the entire interactive infographic locally.

---
---

## 🌐 Versión en Español

### ✨ Infografía Interactiva

Para una exploración completa y visual de este proyecto, te invitamos a ver la **infografía web interactiva**: 
**[➡️ Haz clic aquí para ver la presentación](https://sergiosilveram.github.io/InfografiaProyecto/)**

### 🚀 Resumen del Proyecto

Este repositorio contiene el código fuente de la infografía interactiva y los materiales visuales del proyecto de grado para optar al título de Magíster en Analítica de Datos.

El proyecto desarrolla un **sistema experto híbrido** que integra el poder predictivo del **aprendizaje automático (XGBoost)** con la capacidad de la **lógica difusa** para manejar la incertidumbre. El objetivo es optimizar la gestión de cobranza en una BPO mediante una segmentación de riesgo inteligente y precisa, que permita priorizar recursos y diseñar estrategias de cobro personalizadas.

### 🎯 El Problema

La gestión de cobranza tradicional en las BPO a menudo carece de una segmentación de riesgo precisa, lo que resulta en:
* Una **asignación ineficiente de recursos**.
* Bajas tasas de recuperación de cartera.
* Falta de estrategias personalizadas para los deudores.

Este proyecto aborda la siguiente pregunta: 
> *¿Cómo puede una BPO en Colombia optimizar la gestión y recuperación de cartera vencida mediante un sistema inteligente que combine técnicas de aprendizaje automático y lógica difusa, con el fin de segmentar clientes y diseñar estrategias de cobranza personalizadas, considerando las características de los datos disponibles?*

### 💡 La Solución Propuesta

Se diseñó y construyó un sistema experto que sigue una metodología robusta en varias fases:

1.  **Análisis Exploratorio de Datos (EDA):** Comprensión profunda de los datos, identificando desbalances y características clave.
2.  **Benchmark de Modelos:** Se compararon rigurosamente múltiples algoritmos (Regresión Logística, Árboles de Decisión, Random Forest, SVM, XGBoost) utilizando un esquema de **Validación Cruzada Anidada** para garantizar la robustez.
3.  **Selección del Campeón:** El modelo **XGBoost** demostró el mejor rendimiento general, con un **AUC de 0.96** y un **F1-Score de 0.825**.
4.  **Sistema de Inferencia Difusa:** La probabilidad arrojada por XGBoost se integró como entrada a un sistema de lógica difusa para traducir el riesgo numérico en **segmentos lingüísticos interpretables** (Riesgo Muy Bajo, Bajo, Medio, Alto, Crítico).
5.  **Explicabilidad (XAI):** Se utilizaron técnicas como **LIME** para asegurar la interpretabilidad del modelo, un requisito crucial en el sector financiero.

### 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, Tailwind CSS, JavaScript
* **Visualización de Datos:** Chart.js
* **Modelado (offline):** Python, Scikit-learn, XGBoost, Optuna, Skfuzzy
* **Hosting:** GitHub Pages

### 📂 Estructura del Repositorio

```bash
/
├── images/             # Contiene todas las imágenes y gráficos del proyecto.
├── index.html          # El archivo principal de la infografía interactiva.
└── README.md           # La documentación que estás leyendo.
```

### 🚀 Cómo Usar

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/SergioSilveraM/InfografiaProyecto.git](https://github.com/SergioSilveraM/InfografiaProyecto.git)
    ```
2.  **Abre el archivo `index.html`:**
    Navega a la carpeta del proyecto y abre el archivo `index.html` en tu navegador web preferido (Google Chrome, Firefox, etc.).

¡Y listo! Podrás explorar toda la infografía interactiva localmente.
