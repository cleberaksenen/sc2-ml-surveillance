# 🧬 Enhancing SARS-CoV-2 Surveillance with qPCR Protocols and Machine Learning

This project integrates data science, molecular biology, and machine learning to enhance SARS-CoV-2 lineage surveillance through an optimized qPCR protocol and advanced classification models. By combining genomic analysis with machine learning (SVM, Logistic Regression, and Gradient Boosting), it enables highly accurate variant identification, focusing on the BE.9 lineage.

This methodology is scalable, cost-effective, and particularly useful in resource-limited settings, offering a practical alternative to whole-genome sequencing. Additionally, it is a versatile approach, adaptable to other pathogens with relevant molecular signatures.

## 📌 Published in: https://pubs.acs.org/doi/10.1021/acs.analchem.4c04492


## 🚀 Development Workflow
### Step 1 – Molecular Signature Evaluation
Analysis of key genomic markers to differentiate BE.9 from non-BE.9 SARS-CoV-2 lineages.
#### 📌 Key Insight: Identification of a unique deletion within the BE.9 lineage, serving as a molecular signature.

![deletion-detection](https://github.com/user-attachments/assets/14633ce6-1ff9-4f1f-a060-47ca667c754e)

### Step 2 – qPCR Assay Development
Design and optimization of a qPCR-based protocol to detect and differentiate BE.9 and non-BE.9 lineages efficiently.
#### 📌 Outcome: A rapid, cost-effective, and highly specific qPCR assay for SARS-CoV-2 variant detection.

![qPCR-protocol](https://github.com/user-attachments/assets/38a9f98f-b857-4d19-8919-21ab9635ce48)

### Step 3 – Machine Learning for qPCR Curve Analysis
Development of machine learning models to automate and enhance the interpretation of qPCR amplification curves, reducing human error and improving accuracy.
#### 📌 Key Findings: The SVM model demonstrated the highest overall accuracy (97.4%), with strong precision and recall scores across all categories.

| Algorithm           | BE.9 Precision | non-BE.9 Precision | Inconclusive Precision | BE.9 Recall | non-BE.9 Recall | Inconclusive Recall | BE.9 F1-score | non-BE.9 F1-score | Inconclusive F1-score | Accuracy |
|---------------------|----------------|--------------------|------------------------|-------------|------------------|---------------------|---------------|-------------------|-----------------------|----------|
| SVM                 | 0.991          | 0.992              | 0.936                  | 0.974       | 0.968            | 0.981               | 0.983         | 0.980             | 0.960                 | 0.974    |
| Logistic Regression | 1.000          | 0.976              | 0.910                  | 0.932       | 0.984            | 0.971               | 0.965         | 0.980             | 0.940                 | 0.963    |
| Gradient Boosting   | 0.983          | 0.976              | 0.961                  | 0.983       | 0.984            | 0.952               | 0.983         | 0.980             | 0.957                 | 0.974    |

![ML-model](https://github.com/user-attachments/assets/50ef8097-ed0f-4ca4-88b4-d42d91a5c6fd)

### 📌 Key Contributions
✅ Cost-effective qPCR-based surveillance for SARS-CoV-2 variants

✅ Machine learning-enhanced interpretation of qPCR data

✅ High accuracy in BE.9 variant detection (97.4%)

✅ Scalable solution applicable to other pathogens

For more details, check out the full publication: ACS Analytical Chemistry

