# Practical Lab 2: Multivariate Regression & Non-Parametric Models

**Student Name:** Krishna Reddy Bovilla  
**Student ID:** 9050861  
**Course:** Machine Learning Programming (PROG8245) - Foundations of Machine Learning Frameworks  
**Institution:** Conestoga College  

---

## 📌 Objective

The objective of this lab is to explore and compare multiple regression techniques for predicting diabetes progression using the **Scikit-learn Diabetes dataset**.  
The following models are implemented and analyzed:

- **Univariate Polynomial Regression**
- **Multivariate Polynomial Regression**
- **Decision Tree Regression**
- **k-Nearest Neighbors Regression**

Each model is evaluated using:
- **R² (Coefficient of Determination)**
- **MAE (Mean Absolute Error)**
- **MAPE (Mean Absolute Percentage Error)**

---

## 📁 Project Structure

```
Practical-Lab-2/
│
├── Lab2_Regression_Models.ipynb   # Main notebook with all models and analysis
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to set up and run the lab:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/kittuai/Practical-Lab-2.git
cd Practical-Lab-2
```

### 2️⃣ Create & Activate Virtual Environment
```bash
# Create virtual environment
python -m venv env

# Activate:
# Windows CMD
env\Scripts\activate

# Windows PowerShell
.\env\Scripts\Activate.ps1

# macOS/Linux
source env/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Add Virtual Environment to Jupyter
```bash
python -m ipykernel install --user --name=env --display-name "Python (env)"
```

### 5️⃣ Run the Notebook

- Open **Lab2_Regression_Models.ipynb** in **VS Code** or **Jupyter Notebook**.
- Set the kernel to **Python (env)**.
- Run all cells.

---

## 📊 Model Comparison

| Model                     | Characteristics                             | Notes                                              |
|---------------------------|---------------------------------------------|----------------------------------------------------|
| **Univariate Polynomial** | Simple curve using only BMI                 | Misses other important features                    |
| **Multivariate Polynomial** | Multiple features, balanced fit             | Best performance — smooth, generalizable           |
| **Decision Tree**         | Rule-based, stepwise predictions            | Less smooth; performs in discrete chunks           |
| **k-Nearest Neighbors**   | Distance-based, neighborhood predictions    | Can be jumpy and unstable at edges                 |

✅ **Best Model:** The **Multivariate Polynomial Regression** gave the most consistent, interpretable predictions by leveraging multiple features such as `s5`, `bp`, and `s4`.

---

## 📝 Conclusion

The **Multivariate Polynomial Regression** model is the most appropriate for modeling diabetes progression on this dataset because it effectively balances **complexity** and **generalization**.

---

## ✨ Notebook Highlights

- Clean explanations for each model
- Visual analysis for easy interpretation
- Training, validation, and test metrics compared side-by-side
- Beginner-friendly code with helpful markdown cells
- Fully reproducible setup using `venv` and `requirements.txt`

---

