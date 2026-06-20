# Breast Cancer Classification (Benign vs. Malignant)

A machine learning solution to accurately classify breast cancer tumors as either benign or malignant using diagnostic features.

## 🎯 Project Overview
This project focuses on the early detection and classification of breast cancer. By analyzing clinical diagnostic features (such as radius, texture, and perimeter of cell nuclei), the model provides a robust tool for supporting medical diagnosis with high precision.

## 🔬 Methodology
* **Dataset:** Diagnostic dataset consisting of clinical measurements of cell nuclei.
* **Preprocessing & Feature Engineering:** * Handled missing values and performed label encoding for target classes.
    * Applied feature scaling to normalize input data for distance-based algorithms.
* **Models Implemented:**
    * **Logistic Regression:** For baseline probabilistic classification.
    * **Support Vector Machine (SVM):** Used for finding an optimal hyperplane to separate classes in high-dimensional space.
    * **Random Forest:** Utilized as an ensemble method to improve robustness and reduce overfitting.

## 📊 Key Results
* **Accuracy:** Achieved over **96% accuracy** on the diagnostic dataset.
* **Performance:** The models demonstrate high reliability in distinguishing between benign and malignant cases, minimizing false negatives—a critical requirement for medical applications.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib/Seaborn

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis script: `python main.py`

---
*Developed for academic/diagnostic support purposes.*
