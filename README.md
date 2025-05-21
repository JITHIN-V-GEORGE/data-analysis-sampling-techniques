# Data Analysis Project: Sampling Techniques Using Python

This data analysis project demonstrates the application of various **sampling techniques** using Python. The objective is to provide a practical understanding of both **probability** and **non-probability** sampling methods used in statistical analysis. This is achieved by implementing techniques on a real-world CSV dataset, with corresponding Python code, visualizations, and summary statistics.

---

## 📘 Overview

Sampling is a critical component of statistical data analysis. It allows analysts to make informed decisions and inferences about a **population** by studying a **representative subset**, rather than the entire dataset — saving time and resources while maintaining analytical accuracy.

This project covers:
- Definitions and importance of population and sampling
- Comparison between probability and non-probability sampling
- Implementation of each technique using Python
- Visualization and statistical interpretation of results

---

## 👥 Population and Sampling

### 🔹 Population

A **population** refers to the entire group of individuals, items, or data points that share one or more characteristics. In sampling theory, it is the source from which subsets (samples) are drawn.

> Every unit from a given population has the **same probability** of being selected in a **probability sampling** method.

### 🔹 Sampling

**Sampling** is the process of selecting a subset of individuals from a population to estimate characteristics of the whole population. It enables data scientists and analysts to derive meaningful insights without processing the entire dataset.

### ✅ Advantages of Sampling:
- Reduces time and cost
- Ensures feasibility when studying large populations
- Allows statistical inference and generalization

---

## 📊 Sampling Techniques

### 🔸 Probability Sampling Techniques

| Technique                | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Simple Random Sampling   | Randomly selects units from the entire population.                          |
| Systematic Sampling      | Selects every *kth* unit based on a fixed interval.                         |
| Cluster Sampling         | Divides the population into equal-sized clusters and selects entire clusters.|
| Stratified Sampling      | Divides population into subgroups (strata) and samples from each strata.    |

### 🔸 Non-Probability Sampling Techniques

These methods do not give each population unit a known or equal chance of being selected.

- **Convenience Sampling** – Based on availability or ease of access  
- **Quota Sampling** – Sampling until a pre-defined quota is met  
- **Judgment Sampling** – Based on expert opinion or selection  
- **Snowball Sampling** – Participants recruit others to the sample group

---

## 🛠️ Project Contents

| File | Description |
|------|-------------|
| `DA_Sampling.ipynb` | Jupyter/Colab notebook demonstrating sampling methods with analysis |
| `8_da_sampling.py` | Python script version of the notebook |
| `Dataset.csv` | Real-world dataset used for applying sampling techniques |
| `Population & Sampling.pdf` | Conceptual reference document explaining sampling types |

---

## 🧪 Technologies Used

- **Python 3.10+**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Scikit-learn** – Stratified sampling via `StratifiedShuffleSplit`  
- **Google Colab** – Notebook environment for execution  

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn

