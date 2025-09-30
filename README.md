# 🌳 Decision Trees and Random Forests (Heart Disease Prediction)

## 📌 Objective
The goal of this project is to learn and implement **tree-based models** for classification and regression tasks. We explore **Decision Trees** and **Random Forests** using the Heart Disease dataset.

---

## 🛠️ Tools & Libraries
- **Python**
- **Scikit-learn** → Model training & evaluation
- **Graphviz** → Tree visualization
- **Matplotlib / Seaborn** → Plotting feature importance
- **Pandas / NumPy** → Data manipulation

---

## 📂 Dataset
We use the **Heart Disease dataset** with the following features:

| Column     | Description                                  |
|------------|----------------------------------------------|
| age        | Age of the patient                          |
| sex        | Sex (1 = male, 0 = female)                  |
| cp         | Chest pain type                             |
| trestbps   | Resting blood pressure                      |
| chol       | Serum cholesterol (mg/dl)                   |
| fbs        | Fasting blood sugar > 120 mg/dl (1 = true)  |
| restecg    | Resting electrocardiographic results        |
| thalach    | Maximum heart rate achieved                 |
| exang      | Exercise-induced angina                     |
| oldpeak    | ST depression induced by exercise           |
| slope      | Slope of the peak exercise ST segment       |
| ca         | Number of major vessels (0–3) colored by fluoroscopy |
| thal       | Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| target     | Heart disease (1 = yes, 0 = no)             |

---

## 🚀 Steps in the Project

### 1. **Data Preprocessing**
- Load dataset using Pandas
- Split into **train/test sets**
- Standardize features (optional for Random Forests, useful for stability)

### 2. **Decision Tree Classifier**
- Train a decision tree
- Visualize the tree using **Graphviz**
- Compare accuracy with and without depth restriction
- Analyze overfitting

### 3. **Random Forest Classifier**
- Train a Random Forest with multiple trees
- Compare accuracy with a single decision tree
- Visualize and interpret **feature importance**

### 4. **Cross-Validation**
- Use **k-fold cross-validation** to evaluate model stability

---

## 📊 Results
- Decision Tree (unrestricted depth) → High training accuracy, risk of overfitting
- Decision Tree (pruned, depth limited) → Balanced accuracy, better generalization
- Random Forest → Higher accuracy, robust to overfitting
- Feature Importances → Show which features influence predictions most (e.g., `thalach`, `cp`, `oldpeak`)

---

