# Machine Learning – Practical Session 4

**National Higher School of Advanced Technologies (ENSTA)**  
**Academic Year:** 2026–2027

## Overfitting, Data Leakage and Model Generalization

### Overview

This practical session focuses on understanding and investigating three important machine learning concepts:

- **Overfitting:** When a model learns the training data too closely and performs poorly on unseen data.
- **Data Leakage:** When information from outside the training process influences model training, leading to unreliable evaluation results.
- **Model Generalization:** The ability of a trained model to make accurate predictions on new, unseen data.

The practical work uses a student-survey dataset to explore these concepts through data analysis, preprocessing, model training, and evaluation.

### Dataset

The dataset used in this practical session is:

`hybrid_student_performance_1200.csv`

It contains **1,200 student records and 36 columns**, including academic, behavioral, and personal study-related information.

### Main Objectives

- Inspect the dataset and identify missing values and duplicates.
- Investigate potential data leakage risks.
- Understand how preprocessing can affect model evaluation.
- Analyze rare categories and their impact on model performance.
- Identify and prevent overfitting.
- Evaluate model generalization using appropriate validation strategies.

### Repository Structure

```text
machine-learning-tp4/
│
├── TP4_Solution.ipynb
├── hybrid_student_performance_1200.csv
└── README.md
```

### Requirements

- Python 3.12
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel
```

### How to Run

1. Clone the repository:

```bash
git clone https://github.com/soundoushj/machine-learning-tp4.git
```

2. Open the project folder:

```bash
cd machine-learning-tp4
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `ML_Practical_Session_4_Solution_with_Markdowns.ipynb`.

5. Select your Python 3.12 kernel and execute the notebook cells.

### Notes

The notebook contains Markdown explanations and Python code organized according to the practical session.

Make sure the CSV dataset is in the same directory as the notebook before executing it.

---

**Course:** Machine Learning  
**Institution:** National Higher School of Advanced Technologies (ENSTA)  
**Academic Year:** 2026–2027