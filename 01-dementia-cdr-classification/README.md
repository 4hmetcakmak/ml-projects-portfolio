# Dementia Severity (CDR) Classification

Team project, **Coşkunöz Education Foundation Data Science Bootcamp** (2022).

Predicts the global **Clinical Dementia Rating** (`CDRGLOB`, 4 classes) from demographic, cognitive (MoCA), genetic (APOE) and lifestyle features.

| Notebook | Content |
|---|---|
| `01_classification_models_oversampling.ipynb` | ADASYN oversampling, Random Forest, Gradient Boosting, KNN, MLP, XGBoost with HalvingGridSearchCV, ROC curves |
| `02_sklearn_models_eda.ipynb` | EDA, encoding & scaling, SMOTE vs. random oversampling vs. no oversampling |
| `03_regression_models.ipynb` | Regression-based baselines |
| `04_tensorflow_model.ipynb` | Neural network with TensorFlow / Keras |

**Best test accuracy:** Random Forest 0.733 · XGBoost 0.724 · Gradient Boosting 0.723 · MLP 0.722 · KNN 0.706

> **Data:** The dataset was provided for the bootcamp competition under a data-use agreement. It is not redistributed here and notebook outputs have been cleared.

**TR:** Coşkunöz Eğitim Vakfı Veri Bilimi Bootcamp grup projesi. Demografik, bilişsel, genetik ve yaşam tarzı değişkenlerinden klinik demans derecesini (4 sınıf) tahmin eder. Veri seti paylaşım kısıtı nedeniyle eklenmemiştir.
