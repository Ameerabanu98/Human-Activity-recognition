#  Human Activity Recognition Using Smartphone Data

##  Project Overview
This project focuses on classifying human activities using smartphone sensor data. The dataset contains motion data from smartphone accelerometers and gyroscopes, and machine learning models are trained to predict activities such as walking, sitting, and jogging.

##  Dataset
- **Source:** Kaggle
- **Features:** Sensor data from accelerometers & gyroscopes
- **Labels:** Activities like walking, sitting, standing, etc.
- **Size:** Train and test sets with ~10,000+ instances

## 🛠️ Technologies Used
- **Python** 
- **Scikit-learn** 
- **Pandas & NumPy** 
- **Seaborn & Matplotlib** 
- **SMOTE (for handling imbalanced data)** ⚖
- **PCA (Dimensionality Reduction)** 
- **Machine Learning Models:** Logistic Regression, Random Forest, SVM, GaussianNB

##  Preprocessing Steps
1. **Data Cleaning:** Handling missing values and outliers.
2. **Feature Engineering:** Selecting important features.
3. **Data Scaling:** Standardizing sensor data.
4. **Handling Imbalance:** Applying **SMOTE** to balance the dataset.
5. **Dimensionality Reduction:** Using **PCA** to reduce feature space.

##  Model Training & Evaluation
- **Hyperparameter tuning** was applied using `GridSearchCV`.
- **Best performing model:** Support Vector Classifier (SVC) with **91.44% accuracy**.
- **Other models tested:** Random Forest (91.38%), GaussianNB (90.6%), Logistic Regression (89.58%).

##  Results Summary
| Model                     | Accuracy | Precision | Recall | F1 Score |
|---------------------------|----------|-----------|--------|----------|
| **Support Vector Classifier** | **91.44%** | 91.51%    | 91.52% | 91.40%   |
| Random Forest Classifier  | 91.38%   | 91.26%    | 91.16% | 91.19%   |
| GaussianNB               | 90.60%   | 90.73%    | 90.60% | 90.63%   |
| Logistic Regression      | 89.58%   | 89.69%    | 89.70% | 89.57%   |


##  Future Enhancements
Try **Deep Learning** models (LSTMs, CNNs) for better accuracy.
Experiment with **feature selection** techniques to improve performance.
Real-time Prediction – Deploy for live activity recognition.
Edge Optimization – Adapt for smartwatches & IoT devices.

