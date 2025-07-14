# Patient Clustering for Medical Insights & Mortality Prediction 🧠📊

This project leverages machine learning and deep learning techniques on ICU patient data (derived from the MIMIC-III database) to uncover medical insights through clustering and predict post-discharge mortality.

## 📌 Objectives
- Cluster patients based on vital signs and lab test data using KMeans and Hierarchical Clustering
- Predict extra-hospital mortality using an Artificial Neural Network (ANN)
- Extract clinically relevant patterns from ICU data using visual analytics

## 🧪 Data Sources
- **MIMIC-III derived datasets**: Blood glucose, white blood cells, platelet count, respiratory rate, etc.
- **Demographic and administrative attributes**: Age, gender, ethnicity, marital status, medical services

## 🧠 Techniques Used
- **Clustering**: KMeans, Hierarchical Clustering (SciKit-Learn)
- **Prediction**: Neural Network (Keras over TensorFlow)
- **Visualization**: Histograms, Boxplots, Pie Charts (Matplotlib, Seaborn)
- **Imputation**: MICE (Multivariate Imputation by Chained Equations)

## 🧬 Mortality Prediction Categories
- **< 1 month**
- **1 to 12 months**
- **> 12 months**
- Achieved ~0.82 AUROC with high interpretability and balanced classes

## 🗂️ Key Files
- `FAE project1 sanjana.ipynb`: Exploratory data analysis and clustering
- `mortality_labels_prediction.py`: Deep learning model for mortality classification
- `*.csv`: Preprocessed patient-level datasets
- `plots/`: Includes data distribution and architecture images
- `neural_network/`, `features/`, `labels/`, `services/`: Core modular structure

## 📊 Sample Visuals

![Boxplot](plots/normal_distribution.png)
![Glasgow Scale](plots/glasgow_coma_scale.png)
![Schema](plots/mimic_schema.png)

## 🛠️ Tech Stack
- Python 3.x
- Pandas, NumPy, SciKit-Learn
- TensorFlow / Keras
- Matplotlib, Seaborn

---

> 🚨 All patient data is derived from the publicly available, de-identified MIMIC-III dataset.
