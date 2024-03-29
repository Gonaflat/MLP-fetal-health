# MLP-fetal-health
Multiclass Classification - FETAL HEALTH PREDICTION
# Introduction
Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress.
The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births.

Parallel to notion of child mortality is of course maternal mortality, which accounts for 295 000 deaths during and following pregnancy and childbirth (as of 2017). The vast majority of these deaths (94%) occurred in low-resource settings, and most could have been prevented.

In light of what was mentioned above, Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.
# Data
This dataset contains 2126 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetritians into 3 classes:
- Normal
- Suspect
- Pathological
# What was applied?
- Data preprocessing.
  - Processing of missing values and duplicates.
  - Initial visualization: Box Plot (for outlier visualization), Histograms (for distribution visualization).
  - The Winsorize method for outliers treatment
  - Transformation of Y (classes) into One-Hot-Encoding format
  - Smote method
# What models and evaluation were applied?
- MLP (Multilayer Perceptron),
  - Keras Tuner for hyperparameter,
  - Regularization,
  - Dropout
- Evaluation and Visualization Methods
  - Test accuracy, Test Loss,
  - Accuracy and validation score graph,
  - Confusion Matrix
