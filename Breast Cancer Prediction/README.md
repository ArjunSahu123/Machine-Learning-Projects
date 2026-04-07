# 🧬 Breast Cancer Prediction

Breast cancer prediction is a **binary classification problem** where the goal is to determine whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)**. In this project, we use a dataset built from **digitized images of Fine Needle Aspirate (FNA) samples**, which capture microscopic details of breast tissue.

Instead of relying on visual inspection alone, the dataset provides **quantitative measurements of cell nuclei**, making it suitable for training machine learning models.

---

## 📊 Dataset Overview

Each record in the dataset represents a single sample and includes:

* **ID Number** → A unique identifier for each observation
* **Diagnosis** → Target variable:

  * `M` → Malignant
  * `B` → Benign

---

## 🔬 Features Used

For every cell nucleus in the image, several numerical features are extracted. These describe the **shape, texture, and structure** of the nucleus:

* **Radius** → Average distance from the center to the boundary
* **Texture** → Variation in grayscale intensity
* **Perimeter** → Length of the boundary
* **Area** → Size of the nucleus
* **Smoothness** → Consistency of radius values
* **Compactness** → Measure of how tightly packed the shape is
* **Concavity** → Presence of inward curves along the boundary
* **Concave Points** → Number of concave regions
* **Symmetry** → Degree of balance in shape
* **Fractal Dimension** → Indicates boundary complexity

---

## 🎯 Objective

The main goal of this project is to build a machine learning model that can **accurately classify tumors as malignant or benign** based on these features.

Such models can act as a **support tool for early diagnosis**, helping medical professionals make faster and more informed decisions.

---

## 🚀 Why This Matters

Early detection plays a critical role in successful treatment. By leveraging data-driven approaches, we can improve diagnostic accuracy and potentially assist in saving lives.

