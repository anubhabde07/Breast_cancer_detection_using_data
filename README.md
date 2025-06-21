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


