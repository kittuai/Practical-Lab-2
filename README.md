#  Lab 2: Multivariate Regression & Non-Parametric Models

**Student Name:** Krishna Reddy Bovilla  
**Student ID:** 9050861  
**Course:** Machine Learning Programming (PROG8245)  
**Institution:** Conestoga College  

---

##  Objective

The goal of this lab is to explore different regression techniques using the Scikit-learn Diabetes dataset. Specifically, we compare:

- Univariate Polynomial Regression
- Multivariate Polynomial Regression
- Decision Tree Regression
- k-Nearest Neighbors Regression

Each model is evaluated based on its ability to predict diabetes progression, using R², MAE, and MAPE metrics.

---

##  Project Structure

```
Practical-Lab-2/
│
├── Lab2_Regression_Models.ipynb   # Main notebook with all models and analysis
├── requirements.txt               # All required packages
└── README.md                      # Project documentation
```

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kittuai/Practical-Lab-2.git
cd Practical-Lab-2
```

### 2. Set Up Virtual Environment

```bash
python -m venv env
```

Activate it:

- **Windows CMD:** `env\Scripts\activate`  
- **PowerShell:** `.\env\Scripts\Activate.ps1`  
- **macOS/Linux:** `source env/bin/activate`

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Add Jupyter Kernel

```bash
python -m ipykernel install --user --name=env --display-name "Python (env)"
```

### 5. Run the Notebook

1. Launch VS Code  
2. Open `Lab2_Regression_Models.ipynb`  
3. Set kernel to **Python (env)**  
4. Run all cells

---

##  Model Summary & Comparison

| Model                          | Characteristics                                         | Notes                                                        |
|-------------------------------|----------------------------------------------------------|--------------------------------------------------------------|
| **Univariate Polynomial**      | Simple curve fit with only BMI                         | Misses other influential features                            |
| **Multivariate Polynomial**    | Uses multiple features, more balanced fit              | **Best performance** — smooth, generalizable predictions     |
| **Decision Tree Regressor**   | Rule-based, stepwise predictions                       | Less smooth; performs in chunks                              |
| **kNN Regressor**              | Distance-based; uses neighborhood for prediction       | Jumpy and unstable at the edges                              |

---

##  Final Model Insight

After comparing all models, the **Multivariate Polynomial Regression** model produced the most consistent and interpretable predictions when BMI was varied. It effectively balances complexity and generalization by leveraging multiple features such as `s5`, `bp`, and `s4`.

> **Conclusion:**  
> The Multivariate Polynomial Regression model is the most appropriate for modeling diabetes progression in this dataset.

---

##  Key Features of the Notebook

-  Clear explanation of each regression model
-  Visual analysis for model interpretation
-  Metrics comparison across training, validation, and test sets
-  Clean, beginner-friendly code with markdown guidance
-  Fully reproducible using `venv` and `requirements.txt`

---



