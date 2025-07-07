# 🌾 Smart Crop Recommendation System using Machine Learning

This project presents a machine learning-based solution to assist farmers in selecting the most suitable crop based on environmental and soil parameters. By leveraging data-driven predictions, it aims to improve crop yield, resource utilization, and support sustainable agriculture.

---

## 📌 Project Overview

This crop recommendation system uses a variety of soil features such as:

- **Nitrogen (N)**
- **Phosphorus (P)**
- **Potassium (K)**
- **Temperature**
- **Humidity**
- **pH value**
- **Rainfall**

These features are used to train a machine learning model that predicts the most suitable crop for the given conditions.

---

## 📁 Dataset

- **File:** `Crop_recommendation.csv`
- **Source:** Publicly available agricultural dataset
- **Attributes:**
  - `N`, `P`, `K` - soil nutrient levels
  - `temperature` - in Celsius
  - `humidity` - in %
  - `ph` - soil pH
  - `rainfall` - in mm
  - `label` - target crop

---

## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (for model building)

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

Each model was trained and evaluated using accuracy metrics and confusion matrices to select the best-performing model.

---

## 📊 Visualizations

- Heatmaps for correlation analysis
- Distribution plots of nutrients and other features
- Accuracy comparisons across models

---

## 🏆 Results

### The best-performing model was selected based on:
1. Highest accuracy
2. Lowest misclassification
3. Generalization across unseen samples

---

## 💡 Future Enhancements
1. Deploy the model as a web app using Flask or Streamlit
2. Integrate GPS and real-time weather APIs for dynamic recommendations
3. Add user interface for farmers in local languages

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/crop-recommendation.git
     ```
2. Navigate into the project folder:
   ```bash
   cd crop-recommendation
     ```
3. Open the notebook:
   ```bash
   jupyter notebook "Main.ipynb"
     ```
4. Run the cells step by step to view EDA, training, and predictions.
