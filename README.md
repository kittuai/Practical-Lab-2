# Lab 2 – Multivariate Regression and Non-Parametric Models 
**Course:** Machine Learning Programming (PROG8245)

---

## Repository Access

The full project, including the notebook and dependency files, is available at:

https://github.com/kittuai/Practical-Lab-2.git

To clone the repository locally:

```bash
https://github.com/kittuai/Practical-Lab-2.git
cd Practical-Lab-2
```

Then follow the setup instructions below to configure your environment and run the notebook.

---

## Assignment Context

This notebook was developed as part of a machine learning laboratory assignment. The objectives include:

- Developing and evaluating multiple regression models:
  - Polynomial Regression (Univariate and Multivariate)
  - Decision Tree Regressor
  - k-Nearest Neighbors (kNN)
- Measuring and comparing model performance using:
  - Coefficient of Determination (R²)
  - Mean Absolute Error (MAE)
  - Mean Absolute Percentage Error (MAPE)
- Utilizing the Scikit-learn Diabetes dataset as a case study
- Writing modular, beginner-friendly code with clear structure and documentation

This setup is designed to be easily reproducible and adaptable across different development environments.

---

## Run Jupyter Notebook in an Isolated Python Environment (VS Code)

This repository contains a Jupyter Notebook and a `requirements.txt` file configured to run in a clean, isolated Python environment using `venv` and Visual Studio Code. This setup ensures reproducibility, avoids dependency conflicts, and provides a robust development workflow for machine learning projects.

---


## Project Structure

```
project-folder/
│
├── your_notebook.ipynb         # Main notebook file
├── requirements.txt            # List of Python dependencies
└── README.md                   # Environment setup and project details
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

Install all dependencies listed in the `requirements.txt` file:

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

1. Launch Visual Studio Code and open the project folder.
2. Open the notebook file (`your_notebook.ipynb`).
3. Use the kernel selector at the top right to choose: **Python (env)**.
4. Run the notebook cells to execute the analysis.

---

## Advantages of This Setup

- **Isolation**: Keeps project dependencies separate from global Python packages.
- **Reproducibility**: Ensures consistent results across different systems.
- **VS Code Integration**: Seamless operation within the Visual Studio Code environment using the Python and Jupyter extensions.

---

## Author

**Name:** Krishna Reddy Bovilla  
**Student ID:** 9050861  
**Institution:** conestoga college

---
