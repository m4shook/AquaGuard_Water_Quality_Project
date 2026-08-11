# AquaGuard — Water Quality Prediction

**Project Owner / Maintainer: Mashook**

A customized and extended water-potability ML project. It predicts potable vs non-potable water from physicochemical measurements.

## Improvements
- Leakage-safe preprocessing: imputation, scaling and SMOTE are fitted only on training data/folds.
- Duplicate removal.
- Logistic Regression, SVM, Random Forest and XGBoost comparison.
- Stratified 5-fold cross-validation.
- Accuracy, precision, recall, F1 and ROC-AUC.
- Validation-based probability-threshold optimization.
- Confusion matrix and ROC curve.
- Feature importance.
- Reusable prediction function.
- AquaGuard ML risk indicator (not a laboratory/regulatory certification).

## Run
Keep `AquaGuard_Water_Quality_Prediction_Mashook.ipynb` and `water_potability.csv` together and run all cells.

Packages: numpy, pandas, matplotlib, scikit-learn, imbalanced-learn, xgboost.

## Attribution
This customized version is based in part on an MIT-licensed upstream project by Amin Rezaeeyan. The original copyright notice is retained as required by the MIT license. Mashook is the owner/maintainer of the customized version; this does not erase the upstream author's copyright in derived portions.

## Disclaimer
This is an academic ML project. Predictions are not a laboratory test, medical recommendation, or regulatory certification.
