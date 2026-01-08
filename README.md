# Medical Insurance Cost Prediction using Linear Regression

## 📌 Objective
The objective of this project is to **predict medical insurance claim charges** based on personal attributes such as age, BMI, smoking status, and other related factors using a **Linear Regression model**.

This project helps in understanding how different features impact insurance costs and serves as a beginner-friendly introduction to regression modeling.

---

## 📊 Dataset
**Medical Cost Personal Dataset**

### Features:
- `age` – Age of the individual
- `sex` – Gender (male/female)
- `bmi` – Body Mass Index
- `children` – Number of children
- `smoker` – Smoking status (yes/no)
- `region` – Residential region
- `charges` – Medical insurance cost (**Target Variable**)

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded dataset using Pandas
- Inspected data using:
  - `.head()`
  - `.info()`
  - `.describe()`
  - `.unique()` and `.value_counts()`

---

### 2️⃣ Data Preprocessing
- Converted categorical variables (`sex`, `smoker`, `region`) into numerical format
- Used one-hot encoding for region
- Checked for missing values

---

### 3️⃣ Feature Selection
- Input features (`X`) were selected by dropping the target column `charges`
- Target variable (`y`) set as `charges`

---

### 4️⃣ Train-Test Split
- Split data into:
  - **80% training data**
  - **20% testing data**

---

### 5️⃣ Model Training
- Trained a **Linear Regression model** using Scikit-learn
- Fitted the model on training data

---

### 6️⃣ Model Evaluation
The model was evaluated using:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error(RMSE)**  
