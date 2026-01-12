# Bagging Classifier (From Scratch in Python)

A clean, from-scratch implementation of a **bagging (bootstrap aggregating) ensemble classifier** using custom decision trees and majority voting.

![Python](https://img.shields.io/badge/Python-3.x-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-blue)

---

## Overview

This project demonstrates how **bagging** works internally by building everything manually—without relying on prebuilt machine learning models.

It focuses on:
- Bootstrap sampling  
- Training multiple base models  
- Combining predictions with majority voting  
- Understanding how ensembles reduce variance  

---

## Features

• Bootstrap sampling (with replacement)  
• Custom decision tree classifiers  
• Majority-vote ensemble prediction  
• Transparent step-by-step outputs  
• Validation testing  

---

## How It Works

1. Multiple bootstrap samples are created from the dataset  
2. A decision tree is trained on each sample  
3. Each model makes a prediction  
4. Final prediction is chosen by majority vote  

This improves stability and reduces overfitting.

---

## Results

Because the dataset is small, this project highlights how:

• Individual models may disagree  
• Voting stabilizes predictions  
• Some contradictions can’t be resolved  
• Bagging improves consistency  

---

## Tech Stack

• Python  
• Jupyter Notebook  
• Ensemble Learning  

---

## How to Run

1. Open `Project5_BaggingIMPROV.ipynb`  
2. Run all cells top to bottom  
3. Review printed outputs  

---

## Project Structure

```
bagging-classifier-python/
├── README.md
├── Project5_BaggingIMPROV.ipynb
├── outputs/
└── report/
    └── Project5_BaggingIMPROV.pdf
```

---

## What I Learned

• How bagging reduces variance  
• Why bootstrap sampling matters  
• How majority voting stabilizes predictions  
• How small datasets affect performance  

---

## Author

Victoria St. John  
University of Missouri–St. Louis  
BS Computer Science  

https://github.com/vstjohn
