# Cyberbullying Detection on Twitter: One-Step vs Two-Step Classification

This repository contains the implementation and experiments for the research study **"Cyberbullying Detection on Twitter: A Performance Comparison of One-Step vs Two-Step Classification Approaches."**  

The project explores different machine learning approaches to detect and categorize cyberbullying content on social media platforms, specifically Twitter.

📄 Paper: https://ieeexplore.ieee.org/document/11101479

---

## Abstract

Cyberbullying detection on social media platforms, especially on Twitter, is crucial for ensuring online safety and addressing harmful online behaviors. As cyberbullying becomes more common, automatic detection systems are essential for identifying abusive content and protecting users. This study compares two classification approaches: a one-step approach and a two-step approach, for detecting and categorizing cyberbullying content. The one-step approach classifies tweets into various categories of cyberbullying, while the two-step approach first determines whether a tweet contains cyberbullying or not, and then classifies it into specific categories if it does. We evaluate the performance of both models using three machine learning algorithms: Random Forest, XGBoost, and SVM, all optimized through hyperparameter tuning. The results show that the two-step approach outperforms the one-step approach, achieving an overall accuracy of **91% compared to 84% for the one-step approach**. XGBoost performs the best for binary classification, while SVM performs best in multiclass categorization. These results highlight the potential of the two-step approach in providing a more detailed understanding of cyberbullying and its types.

---

## Project Overview

The goal of this research is to evaluate two different classification strategies for cyberbullying detection:

### One-Step Classification
- Directly classifies tweets into multiple cyberbullying categories.
- Performs **multiclass classification in a single stage**.

### Two-Step Classification
1. **Binary Classification**  
   Determine whether a tweet contains cyberbullying or not.
2. **Multiclass Classification**  
   If cyberbullying is detected, classify the tweet into specific categories.

This hierarchical approach helps improve detection accuracy and classification clarity.

---

## Machine Learning Models

The following algorithms were evaluated:

- **Random Forest**
- **XGBoost**
- **Support Vector Machine (SVM)**

All models were optimized using **hyperparameter tuning** to achieve the best performance.

---

## Key Results

| Approach | Accuracy |
|--------|--------|
| One-Step Classification | 84% |
| Two-Step Classification | **91%** |

Additional insights:

- **XGBoost** performs best for **binary cyberbullying detection**
- **SVM** performs best for **multiclass cyberbullying categorization**

These results indicate that a **two-step classification pipeline improves performance and interpretability** for cyberbullying detection tasks.

---

---

## Methodology

The project follows the typical NLP and machine learning pipeline:

1. **Data Collection**
2. **Text Preprocessing**
   - Cleaning
   - Tokenization
   - Stopword removal
3. **Feature Engineering**
4. **Model Training**
5. **Hyperparameter Tuning**
6. **Model Evaluation**

---

## Technologies Used

- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Jupyter Notebook

---

## Research Contribution

This research demonstrates that **a hierarchical two-step classification approach improves cyberbullying detection accuracy** and provides better insight into the types of abusive behavior present in social media conversations.

The study contributes to the development of **more effective automated moderation tools** for online platforms.

---

## Citation

If you use this work, please cite the paper:

```
Cyberbullying Detection on Twitter: A Performance Comparison of One-Step vs Two-Step Classification Approaches.
IEEE Xplore, 2025.
https://ieeexplore.ieee.org/document/11101479
```

---

## Author

**Davin Edbert**  
Computer Science Student | Data Science & Machine Learning Enthusiast
