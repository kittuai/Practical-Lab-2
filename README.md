# Lab 2 – Multivariate Regression and Non-Parametric Models

**Student Name:** Krishna Reddy Bovilla  
**Student ID:** 9050861  
**Course:** Machine Learning Programming (PROG8245)  
**Institution:** Conestoga College

---

## Repository Access

The complete project, including the assignment notebook and environment configuration, is hosted at:

To clone the repository locally:

```bash
git clone https://github.com/kittuai/Practical-Lab-2.git
cd Practical-Lab-2
```

---

## About the Assignment

This notebook was developed for **Lab 2: Multivariate Regression and Non-Parametric Models**, a practical component of the Machine Learning Programming course. The lab focuses on building and comparing different regression models using the **Scikit-learn Diabetes dataset**, with special attention to:

- Understanding and applying multiple modeling techniques:
  - Univariate Polynomial Regression
  - Multivariate Polynomial Regression
  - Decision Tree Regressor
  - k-Nearest Neighbors Regressor (kNN)
- Evaluating models using key regression metrics:
  - R² (Coefficient of Determination)
  - MAE (Mean Absolute Error)
  - MAPE (Mean Absolute Percentage Error)
- Using a consistent train–validation–test split
- Writing clean, beginner-friendly Python code with professional structure and clear inline comments
- Presenting visual insights to support interpretation and analysis

---

## Project Structure

```
Practical-Lab-2/
│
├── Lab2_Regression_Models.ipynb  # Main notebook with all model comparisons
├── requirements.txt              # List of Python dependencies
└── README.md                     # Setup instructions and project documentation
```

---

## Prerequisites

To run this project, ensure the following are installed:

- Python 3.8 or higher
- Visual Studio Code
- VS Code Extensions:
  - Python
  - Jupyter

---

## Setup Instructions

### 1. Create a Virtual Environment

```bash
python -m venv env
```

### 2. Activate the Environment

- **Windows (CMD):**
  ```bash
  env\Scripts\activate
  ```
- **Windows (PowerShell):**
  ```powershell
  .\env\Scripts\Activate.ps1
  ```
- **macOS/Linux:**
  ```bash
  source env/bin/activate
  ```

---

### 3. Install Required Dependencies

Install all required libraries from `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

### 4. Register the Environment as a Jupyter Kernel

```bash
python -m ipykernel install --user --name=env --display-name "Python (env)"
```

---

### 5. Open and Run the Notebook

1. Launch **Visual Studio Code**
2. Open the `Practical-Lab-2` folder
3. Open `Lab2_Regression_Models.ipynb`
4. Select the kernel **Python (env)** from the top-right kernel picker
5. Run all cells to explore and compare the models

---

## Key Features

-  Multiple model comparisons in one structured notebook
-  Visual plots to support evaluation of model performance
-  Clean and modular code following best practices
-  Fully reproducible workflow using virtual environments
-  Designed for educational clarity and technical depth

---

## Problem Framing & Final Model Insights

The primary objective was to predict the **progression of diabetes** in patients based on 10 input features from the Scikit-learn Diabetes dataset. The problem was framed as a supervised regression task.

After training and evaluating all models, the following observations were made:

- **Univariate Polynomial Regression** captured nonlinear trends but was limited by using only one feature.
- **Multivariate Polynomial Regression** improved performance slightly but was prone to overfitting with higher degrees.
- **Decision Tree Regressor** offered strong interpretability and handled nonlinearity well, but was sensitive to depth and prone to variance.
- **k-Nearest Neighbors** provided smooth predictions but required careful tuning of the number of neighbors.

📌 **Best Performing Model:**  
Based on the R² score and error metrics across validation and test sets, the **Decision Tree Regressor** emerged as the most effective model, striking a balance between accuracy and interpretability for this dataset.

---

