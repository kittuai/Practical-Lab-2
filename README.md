# IR_InvertedMatrix_Workshop

**Course:** Machine Learning Programming  
**Institution:** Conestoga College  
**Team Number:** 5

**Team Members:**  
- Mandeep Singh (ID: 8989367)  
- Kumari Nikitha Singh (ID: 9053016)  
- Krishna (ID: 905861)

---

## Objective

This workshop implements a simple but realistic **Inverted Index** with positional information.  
We apply standard Information Retrieval (IR) techniques on real text to show how search systems store and match words and phrases efficiently.

---

## Repository

**GitHub Repo:**  
[IR-invertedmatrix-workshop](https://github.com/kittuai/IR-invertedmatrix-workshop.git)

---

## Contents

- **IR_InvertedMatrix_Workshop.ipynb** — Jupyter notebook with:
  - Document collection
  - Tokenizer
  - Normalization pipeline
  - Positional inverted index
  - Queries and results
- **README.md** — This file with all project details.

---

## Getting Started

1. **Clone the Repository**
   ```
   git clone https://github.com/kittuai/IR-invertedmatrix-workshop.git
   cd IR-invertedmatrix-workshop
   ```

2. **Set Up a Virtual Environment**
   ```
   python -m venv env
   ```

   **Activate it:**  
   - **Windows (CMD):** `env\Scripts\activate`  
   - **PowerShell:** `.\env\Scripts\Activate.ps1`  
   - **macOS/Linux:** `source env/bin/activate`

3. **Install Requirements**
   *(Install any packages you need for the notebook)*  
   ```
   pip install scikit-learn nltk jupyter
   ```

4. **Add Jupyter Kernel**
   ```
   python -m ipykernel install --user --name=env --display-name "Python (env)"
   ```

5. **Run the Notebook**
   - Open `IR_InvertedMatrix_Workshop.ipynb` in VS Code or Jupyter Lab.
   - Set the kernel to **Python (env)**.
   - Run all cells step by step.

---

## Key Learning

- How to tokenize and normalize text.
- How an inverted index maps terms to documents.
- How positional indexing supports phrase queries.
- How to test queries with clear results.

---

## Final Note

This notebook shows the core IR pipeline behind modern search.  
It is a practical base for more advanced indexing and ranking methods.

**Submitted for:** PROG8245 — Machine Learning Programming
