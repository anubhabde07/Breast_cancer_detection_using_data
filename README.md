# Breast_cancer_detection_using_data

This project uses a neural network built with TensorFlow and Keras to classify tumors as **malignant** or **benign** based on the **Breast Cancer Wisconsin Diagnostic Dataset**.

---

##  Dataset

 **Source**: [Breast Cancer Wisconsin Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
 **Rows**: 569 samples
 **Features**: 30 numeric features related to mean, standard error, and worst values of cell nuclei measurements
 **Target**:
  `M` = Malignant
  `B` = Benign


##  Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib (optional, for visualization)

---

##  Model Overview

 **Input shape**: 30 features  
 **Architecture**:
 Dense layers with ReLU activations  
 Sigmoid output layer for binary classification  
 **Loss Function**: Binary Crossentropy  
 **Optimizer**: Adam

---

##  Accuracy
 Achieved **~88%–96% accuracy** on the test data.  
 You can improve this further with hyperparameter tuning, class balancing, and regularization.
---

## Inpupt Format (2D array)
[
 'radius_mean', 'texture_mean', 'perimeter_mean', 'area_mean',
 'smoothness_mean', 'compactness_mean', 'concavity_mean',
 'concave points_mean', 'symmetry_mean', 'fractal_dimension_mean',
 'radius_se', 'texture_se', 'perimeter_se', 'area_se', 'smoothness_se',
 'compactness_se', 'concavity_se', 'concave points_se', 'symmetry_se',
 'fractal_dimension_se', 'radius_worst', 'texture_worst',
 'perimeter_worst', 'area_worst', 'smoothness_worst',
 'compactness_worst', 'concavity_worst', 'concave points_worst',
 'symmetry_worst', 'fractal_dimension_worst'
]



