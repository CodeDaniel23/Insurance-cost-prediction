# Insurance Cost Prediction (Machine Learning)

This project predicts **insurance charges** using Machine Learning in Python.


## 📌 Project Goal
To build a regression model that can estimate insurance charges based on features like:
- age
- BMI
- children
- sex
- smoker
- region


## 🛠️ Tech Stack / Libraries
- Python
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn (if used)


## 📂 Dataset
The dataset contains insurance customer details and the target column:
- **charges** (Target)


## Workflow
### 1) Data Loading
- Loaded CSV dataset using pandas

### 2) Data Understanding
- `df.head()`
- `df.shape`
- `df.info()`
- `df.describe()`

### 3) Data Cleaning
- Checked missing values
- Handled duplicates (if any)
- Prepared clean dataset for ML

### 4) EDA (Exploratory Data Analysis)
- Visualized important patterns (age, BMI, smoker vs charges, etc.)
- Checked relationships and trends

### 5) Feature & Target Selection
- **X** = all columns except `charges`
- **y** = `charges`

### 6) Model Training
- Train/Test split
- Trained regression model

### 7) Model Evaluation
Evaluation metrics used:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R2 Score


## 📊 Output
After running the notebook, you will get:
- predicted charges
- model accuracy metrics (MAE, RMSE, R2)


## ▶️ How to Run
1. Open the notebook: `insurance-cost-prediction.ipynb`
2. Run all cells from top to bottom


## 📁 Folder Structure
insurance-cost-prediction/
│── insurance-cost-prediction.ipynb
│── README.md
└── insurancedata_link/
    └── insurance.csv


## 🚀 Future Improvements (Optional)
- Try Ridge / Lasso Regression
- Hyperparameter tuning
- Feature scaling & feature engineering
- Build a Streamlit app for deployment


## 👤 Author
White | GitHub: CodeDaniel23