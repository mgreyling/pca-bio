# PCA on Breast Cancer Dataset

This project applies **Principal Component Analysis (PCA)** to a breast cancer dataset to explore patterns in high-dimensional gene-related features. The goal is to reduce 30 features to 2 principal components and visualize the separation between malignant and benign samples.

## Dataset

- Source: [Wisconsin Diagnostic Breast Cancer (WDBC) Dataset, UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- 569 samples, 30 numerical features related to cell nuclei
- Labels: Malignant (`M`) or Benign (`B`)

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib

## Project Workflow

1. **Data Loading** – Downloaded dataset and separated features (`X`) from target labels (`y`).
2. **Standardization** – Standardized features to ensure all variables contribute equally to PCA.
3. **Dimensionality Reduction** – Applied PCA to project data onto the first two principal components.
4. **Visualization** – Plotted samples in 2D space colored by label to observe separation.
5. **Conclusion** – PCA reduced 30 features to 2 components. The plot shows partial separation between malignant and benign samples, indicating meaningful low-dimensional structure in the data.
