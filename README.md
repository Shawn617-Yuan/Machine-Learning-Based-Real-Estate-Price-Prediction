# Machine-Learning-Based-Real-Estate-Price-Prediction

**An extensive analysis of the Ames, Iowa residential homes dataset to identify the best regression model for house price prediction.**

## In this work, I used different types of technologies:
1. Polynomial Regression
2. Support Vector Machine Regression
3. Random Forest Regression
4. Principal Component Analysis
5. t-SNE

## Methodology:
**Data Imputation:** Utilized Regression Imputation with label encoding for missing data handling.  
**Dimensionality Reduction:** Found PCA to be less effective for this dataset. Increasing PCA components improved performance, but not as initially expected.  
**Best Performing Model:** Random Forest Regression outperformed other models. Key impactful features included overall quality, living area, garage size, and basement area.

## Conclusions and Future Work:
**Data Preprocessing and Encoding:** Explored both label and one-hot encoding, finding similar cross-validation scores. Identified the need for careful encoding and imputation method selection.

**Limitations and Improvements:**
1. Importance of data preprocessing and feature correlation analysis in the EDA process.
2. Potential exploration of more advanced regression models (e.g., AdaBoost, XGBoost) and neural networks using PyTorch for enhanced performance.
