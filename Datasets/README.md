# 📂 Datasets for ML Internship Projects

This folder contains links and descriptions of the datasets used in my **Machine Learning Internship projects at Unified Mentor Pvt Ltd**.  
Due to GitHub’s file size limitations (25 MB), full datasets are hosted externally. 

---

## 🐾 1. Animal Image Classification Dataset
- **Description:**  
  This dataset contains **15 folders of animal images** resized to `224x224x3`.  
  Each folder represents one class.

- **Classes:**  
  `Bear, Bird, Cat, Cow, Deer, Dog, Dolphin, Elephant, Giraffe, Horse, Kangaroo, Lion, Panda, Tiger, Zebra`

- **Size:** ~15,000+ images (15 categories)  
- **Download Link:** [📥 Animal Dataset (Google Drive)](https://drive.google.com/file/d/1BnyNQptNMumYisu9u7Ln29EkQFhcWaoA/view?usp=sharing)  
- **Usage in Project:** Used for training an **EfficientNetB0** model for multi-class classification.

---

## 📱 2. Mobile Price Prediction Dataset
- **Description:**  
  Mobile phone specifications dataset with **2000 samples and 21 features**.  
  The target variable is `price_range` (0 = Low, 1 = Medium, 2 = High, 3 = Very High).

- **Features Include:**  
  `battery_power, ram, px_height, px_width, dual_sim, n_cores, talk_time, 4g, 3g, wifi, ...`

- **Size:** ~300 KB (CSV)  
- **Download Link:** [📥 Mobile Price Dataset (Google Drive)](https://drive.google.com/file/d/1LXgMdxMHu45tjNmjjLUKpsSfNGlzHmxt/view?usp=sharing)  
- **Usage in Project:** Used for building an **XGBoost Classifier**, achieving **92.4% accuracy**.

---

## 🫁 3. Lung Cancer Survival Prediction Dataset
- **Description:**  
  Medical dataset with **~890,000 rows and 48 features** related to patient history, treatments, and survival outcomes.  
  Target variable: `survived` (binary classification).

- **Features Include:**  
  `age, gender, BMI, cholesterol, hypertension, asthma, smoking_status, cancer_stage, treatment_type, ...`

- **Size:** ~120 MB (CSV)  
- **Download Link:** [📥 Lung Cancer Dataset (Google Drive)](https://drive.google.com/file/d/18bOOesmBVR1PcIkWOSxjjlphIy9Kzp0f/view?usp=sharing)  
- **Usage in Project:** Used for training **Logistic Regression & XGBoost models**, achieving ~78% accuracy.

---

## ⚠️ Notes
- Please use the **Google Drive links** above to download the datasets.  
- Ensure correct folder structure for image datasets (e.g., `dataset/Cat/`, `dataset/Dog/`, ...).

---
