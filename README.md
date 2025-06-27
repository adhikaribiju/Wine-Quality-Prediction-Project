# Wine Quality Prediction

**Authors:** Bijay Adhikari, Saurav Dahal
**Contact:** [badhika2@gmail.com](mailto:badhika2@gmail.com), [sdahal4@ramapo.edu](mailto:sdahal4@ramapo.edu)

---

## Abstract

We analyze the Portuguese "Vinho Verde" wine dataset (1,599 samples; 12 chemical features) to predict quality scores (3–8). Using data cleaning, exploratory plots, logistic regression, and K‑means clustering, we identify key predictors—alcohol, volatile acidity, sulphates, and sulfur dioxide levels—and uncover natural wine segments.

---

## Keywords

Wine quality • Logistic regression • Clustering • Chemical analysis

---

## Methods

* **Data:** No missing values; 12 continuous features.
* **EDA:** Density plots and correlation heatmap.
* **Modeling:** Logistic regression (high vs. low quality) with accuracy \~74%.
* **Clustering:** K‑means (K=3) to segment wines by chemical profile.

---

## Key Findings

* **Top predictors:** Alcohol (strongest, p<0.001), volatile acidity (negative, p<0.001), sulphates (p<0.001).
* **Model performance:** Accuracy 73.8%, sensitivity 77.5%, specificity 70.0%.
* **Clusters:** Three groups—lower, average, and higher quality wines—informing marketing and quality control.

---

## Conclusion

Chemical attributes reliably predict wine quality and reveal distinct wine segments, offering actionable insights for producers and marketers.

---

## Data Source

Kaggle: [Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
