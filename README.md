# 📊 Student Performance - Linear Regression from Scratch

This project demonstrates how to build a **Multiple Linear Regression** model from scratch using Python. The dataset used contains academic performance data of students, and the goal is to predict their final scores based on various input features.

---

## 🧠 Objective

To understand and implement the full pipeline of a regression model, including:
- Data preprocessing
- Exploratory data analysis (EDA)
- Feature selection
- Model implementation using NumPy
- Evaluation using R² score

---

## 📁 Dataset

- **Source**: [`Student_Performance.csv`](https://www.kaggle.com/datasets/harshitshankhdhar/student-performance-prediction)
- The dataset includes features like:
  - Hours Studied
  - Previous Scores
  - Sleep Hours
  - Extracurricular Activities
  - and more...

---

## 🛠️ Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
