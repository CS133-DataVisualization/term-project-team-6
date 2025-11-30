# CS 133 Project – Global Video Game Sales

This project analyzes the **Global Video Game Sales** dataset from Kaggle using Python and Jupyter Notebook.  
The main work is in the notebook: `CS_133_Project_Code.ipynb`.

## 1. Environment Setup

### Prerequisites

- **Python** ≥ 3.9
- **pip** (Python package manager)
- **Jupyter Notebook** or **JupyterLab**
- A **Kaggle account** (for accessing the dataset via `kagglehub`)
- Internet connection (to download the dataset from Kaggle)

### Recommended: Create a virtual environment

From the folder containing the notebook:

```bash
# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate

# Windows (PowerShell)
python -m venv .venv
.venv\Scripts\Activate.ps1
```

## 2. Required Packages
The notebook uses the following Python libraries:
 - **numpy** 
 - **pandas**
 - **matplotlib**
 - **seaborn**
 - **scikit-learn**
 - **kagglehub**

 ```bash
 pip install numpy pandas matplotlib seaborn scikit-learn kagglehub
```

## 3. How to Run the Notebook
From the project directory (where CS_133_Project_Code.ipynb is located):

 ```bash
# If your virtual environment isn't active yet, activate it first.
# Then launch Jupyter:
jupyter notebook
# or
jupyter lab
```

In the Jupyter interface:
 1. Navigate to CS_133_Project_Code.ipynb.
 2. Open the notebook.
 3. Run the cells in order (Kernel → Restart & Run All is usually the easiest).

This will:
 - Download the Global Video Game Sales dataset from Kaggle via kagglehub.
 - Perform data loading, preprocessing, and exploratory analysis.
 - Train and evaluate several regression models using scikit-learn.
