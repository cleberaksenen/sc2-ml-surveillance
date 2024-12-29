# Enhancing SARS-CoV-2 Surveillance with qPCR Protocols and Machine Learning

## The project focuses on leveraging data science to monitor emerging SARS-CoV-2 lineages through an optimized qPCR protocol and machine learning algorithms. The approach combines genomic analysis with ML models, such as SVM, to identify variants with high accuracy, highlighting the BE.9 lineage. It is a scalable and cost-effective solution, particularly useful in resource-limited regions, providing a practical alternative to full genomic sequencing. The methodology is versatile and applicable to other pathogens with relevant molecular signatures.
The project is published in: https://pubs.acs.org/doi/10.1021/acs.analchem.4c04492


# Development:
## Step 1 - Evaluation of molecular signatures to differentiate SARS-CoV-2 lineages (BE.9 and non-BE.9)
![deletion-detection](https://github.com/user-attachments/assets/14633ce6-1ff9-4f1f-a060-47ca667c754e)

## Step 2 - Development of qPCR-based assays for differentiating between lineages
![qPCR-protocol](https://github.com/user-attachments/assets/38a9f98f-b857-4d19-8919-21ab9635ce48)

## Step 3 - Development of Machine Learning-based models for automating the analysis of qPCR curves
| Algorithm           | BE.9 Precision | non-BE.9 Precision | Inconclusive Precision | BE.9 Recall | non-BE.9 Recall | Inconclusive Recall | BE.9 F1-score | non-BE.9 F1-score | Inconclusive F1-score | Accuracy |
|---------------------|----------------|--------------------|------------------------|-------------|------------------|---------------------|---------------|-------------------|-----------------------|----------|
| SVM                 | 0.991          | 0.992              | 0.936                  | 0.974       | 0.968            | 0.981               | 0.983         | 0.980             | 0.960                 | 0.974    |
| Logistic Regression | 1.000          | 0.976              | 0.910                  | 0.932       | 0.984            | 0.971               | 0.965         | 0.980             | 0.940                 | 0.963    |
| Gradient Boosting   | 0.983          | 0.976              | 0.961                  | 0.983       | 0.984            | 0.952               | 0.983         | 0.980             | 0.957                 | 0.974    |

![ML-model](https://github.com/user-attachments/assets/50ef8097-ed0f-4ca4-88b4-d42d91a5c6fd)


