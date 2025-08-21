# Heart Disease Prediction using Deep Learning

This project uses **Deep Learning** with **Keras/TensorFlow** to predict the likelihood of heart disease based on clinical and demographic features. The model is trained on a heart disease dataset and optimized using **Keras Tuner** for hyperparameter tuning.

---

## 📌 Features

* Data preprocessing and normalization
* Deep Learning model built with **Keras**
* Hyperparameter tuning using **Keras Tuner (Hyperband)**
* Training/Validation split with performance evaluation
* Metrics: Accuracy, Loss curves, and Confusion Matrix

---

## 🛠️ Technologies Used

* **Python 3.x**
* **TensorFlow / Keras**
* **Keras Tuner** (for hyperparameter optimization)
* **Pandas, NumPy** (data handling)
* **Matplotlib, Seaborn** (visualization)

---

## 📂 Project Structure

```
├── heart-disease-prediction-system-deep-learning.ipynb  # Main notebook
├── README.md                                            # Project documentation
```

---

## 📊 Dataset

The dataset contains patient records with attributes such as:

* Age, Sex
* Chest pain type (cp)
* Resting blood pressure (trestbps)
* Cholesterol (chol)
* Fasting blood sugar (fbs)
* Resting ECG results (restecg)
* Maximum heart rate achieved (thalach)
* Exercise-induced angina (exang)
* Oldpeak (ST depression)
* Slope of peak exercise ST segment
* Number of major vessels colored by fluoroscopy (ca)
* Thalassemia (thal)

**Target variable:** Presence (1) or Absence (0) of heart disease.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook heart-disease-prediction-system-deep-learning.ipynb
```

---

## ⚙️ Hyperparameter Tuning

The model uses **Keras Tuner Hyperband** for selecting:

* Number of layers
* Units per layer
* Activation functions
* Dropout rates
* Learning rate

---

## 📈 Results

* Best Validation Accuracy: **\~100%**
* Test Accuracy: **\~99%** (which shows that no overfitting)

Performance may vary depending on dataset splits and tuning parameters.

---

## 📌 Future Improvements

* Experiment with CNNs/Transformers for tabular data
* Deploy as a web app (Flask/Streamlit)
* Add SHAP/Explainable AI for feature importance

---

## 👨‍💻 Author

Developed by **Haroon Waheed**

---
