# Heart Disease Prediction using Machine Learning

## Overview

This project predicts the likelihood of heart disease using Machine Learning algorithms trained on healthcare data.

The project demonstrates a complete ML workflow including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature scaling
- Model training
- Performance evaluation

The goal is to compare multiple classification algorithms and determine which model performs best for predicting heart disease.

---

## Dataset

Dataset used:

[Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?utm_source=chatgpt.com)

The dataset contains medical attributes such as:

- Age
- Sex
- Cholesterol
- Blood Pressure
- Chest Pain Type
- Maximum Heart Rate
- Exercise Induced Angina

Target Variable:
- `0` → No Heart Disease
- `1` → Heart Disease Present

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

### 1. Data Loading
The dataset is loaded using Pandas.

### 2. Data Exploration
Performed:
- Dataset inspection
- Statistical summary
- Data type analysis

### 3. Data Cleaning
- Duplicate records removed
- Missing values checked

### 4. Exploratory Data Analysis (EDA)

Visualizations created:

- Target variable distribution
- Age histogram
- Cholesterol boxplot
- Correlation heatmap
- Confusion matrix

### 5. Feature Engineering
- Train-test split
- Feature scaling using `StandardScaler`

### 6. Models Trained

The following models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 7. Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Results

The Random Forest Classifier achieved the best overall performance among the tested models.

---

## Project Structure

```text
heart-disease-prediction-ml/
│
├── main.ipynb
├── heart.csv
├── README.md
├── requirements.txt
└── images/
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/heart-disease-prediction-ml.git
```

### 2. Open Project Folder

```bash
cd heart-disease-prediction-ml
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

```bash
jupyter notebook
```

Open:
`main.ipynb`

---

## Future Improvements

Possible improvements for the project:

- Hyperparameter tuning
- ROC-AUC analysis
- Feature importance visualization
- Streamlit deployment
- Deep learning implementation

---

## Author

Muhammad Arbaz  
BS Artificial Intelligence Student

---

## License

This project is for educational and portfolio purposes.