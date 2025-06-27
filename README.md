# day4
AI&ML DAY-4 TASK 
# Logistic Regression – Breast Cancer Classification


##  About the Dataset

- *Dataset Name*: Breast Cancer Wisconsin Data Set
- *Source*: UCI Machine Learning Repository
- *Instances*: 699
- *Attributes*: 10 predictive features + 1 target label (Class)
- *Missing Values*: Some in the Bare_Nuclei column


## Dataset Features (Columns)

| Column Name                  | Description                                      |
|-----------------------------|--------------------------------------------------|
| Sample_code_number          | ID number (not used for prediction)             |
| Clump_Thickness             | Thickness of cell clusters                      |
| Uniformity_of_Cell_Size     | Size uniformity of cells                        |
| Uniformity_of_Cell_Shape    | Shape uniformity of cells                       |
| Marginal_Adhesion           | Cell adhesion capability                        |
| Single_Epithelial_Cell_Size | Size of individual epithelial cells             |
| Bare_Nuclei                 | Nuclei visibility (may contain '?')             |
| Bland_Chromatin             | Chromatin texture uniformity                    |
| Normal_Nucleoli             | Nucleoli characteristics                        |
| Mitoses                     | Mitosis count (cell division indicator)         |
| *Class*                   | Target (2 = Benign, 4 = Malignant)              |

We map the Class column:
- 2 → 0 (Benign)
- 4 → 1 (Malignant)


##  Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Key Results

| Metric     | Value |
|------------|-------|
| Accuracy   | ~96%  |
| Precision  | High  |
| Recall     | High  |
| ROC-AUC    | ~98%  |







