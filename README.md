# 📊 Student Performance Analyzer

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> *This is part of my Data Science learning journey — building projects from Day 1* 🚀

---

## 📌 Project Description

A **NumPy-based Student Performance Analyzer** that analyzes student marks across multiple subjects and generates a complete performance report — without using any loops!

This project demonstrates the power of NumPy for real-world data analysis tasks.

---

## ✨ Features

- 📈 Calculate **average marks** of every student
- 📚 Calculate **average marks** of every subject
- ✅ Determine **Pass / Fail** result for each student
- 🎓 Assign **Grades** (A, B, C, D, F) based on performance
- 🏆 Find the **Top Performer** of the class
- 📉 Identify the **Toughest Subject**
- ⚠️ **Flag subjects** where marks are below 40

---

## 🛠️ NumPy Concepts Used

| Concept | Usage |
|---|---|
| `np.mean(axis=1)` | Student-wise average |
| `np.mean(axis=0)` | Subject-wise average |
| `np.where` | Pass/Fail and Grade assignment |
| `np.argmax` | Finding top performer |
| `np.argmin` | Finding toughest subject |
| `np.reshape` | Clean output formatting |
| Nested `np.where` | Multi-level grade classification |

---

## 📂 Dataset

- **7 Students**
- **5 Subjects**
- Marks range: 0 to 100

```python
marks = np.array([[78, 85, 92, 88, 90],   # Student 1
                  [45, 52, 38, 60, 62],   # Student 2
                  [91, 95, 88, 97, 85],   # Student 3
                  [33, 41, 29, 55, 60],   # Student 4
                  [67, 73, 81, 70, 75],   # Student 5
                  [45, 50, 55, 43, 63],   # Student 6
                  [82, 80, 95, 90, 88]])  # Student 7
```

---

## 📊 Sample Output

```
Average of Every Student :
[[86.6]
 [51.4]
 [91.2]
 [43.6]
 [73.2]
 [51.2]
 [87. ]]

Pass/Fail Result :
[['Pass'] ['Pass'] ['Pass'] ['Fail'] ['Pass'] ['Pass'] ['Pass']]

Grades :
[['B'] ['D'] ['A'] ['Fail'] ['C'] ['D'] ['B']]

Topper of the class is : Student 3
Toughest subject of the class is : Subject 1
```

---

## 🔍 Observations

- **Student 3** is the top performer with an average of **91.2** — Grade A 🏆
- **Student 4** is at risk — low marks in Subject 1 (33) and Subject 3 (29) ⚠️
- **Student 2** needs improvement in Subject 3 (38) ⚠️
- **Subject 1** is the toughest with the lowest class average of **63.0** 📉

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/sohailmohd51/Student-Performance-Analyzer.git
```

**2. Install NumPy**
```bash
pip install numpy
```

**3. Open the notebook**
```bash
jupyter notebook Student_Performance_Analyzer.ipynb
```

Or directly open in **Google Colab** 👇

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FtwrJE0mXH2UGPab56xuvjZHHsf9Ci54?usp=sharing)

---

## 📈 What I Learned

- How to use **NumPy for real data analysis** without loops
- Difference between `axis=0` and `axis=1` operations
- Using **nested np.where** for multi-level classification
- Using **argmax / argmin** to find best and worst performers
- Clean output formatting using **reshape**

---

## 👨‍💻 Author

**Mohammad Sohail Khan**

[![GitHub](https://img.shields.io/badge/GitHub-sohailmohd51-181717?style=for-the-badge&logo=github)](https://github.com/sohailmohd51)

---

⭐ *If you found this project helpful, please give it a star!*
