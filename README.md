# RabTech Academy — Task 3
## Feature Engineering & Preprocessing Pipeline

### Deliverables
- `feature_engineering_preprocessing_pipeline.ipynb` — complete runnable notebook.

### Requirements
Run `pip install pandas numpy scikit-learn matplotlib`, then open the notebook in Jupyter or VS Code and choose **Run All**.

### Included
- Data-quality checks
- Train/test split before transformations
- Numeric imputation and scaling
- Categorical imputation and one-hot encoding
- Reusable `ColumnTransformer` + `Pipeline`
- Logistic regression evaluation
- Mutual-information and permutation feature rankings

### Safety note
This uses scikit-learn's bundled Breast Cancer Wisconsin Diagnostic dataset for education only. It must not be used for real clinical diagnosis. `radius_band` is derived from `mean radius` only to demonstrate categorical encoding.
