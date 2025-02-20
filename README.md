#  Human Activity Recognition Using Smartphone Data

##  Project Overview
This project focuses on classifying human activities using smartphone sensor data. The dataset contains motion data from smartphone accelerometers and gyroscopes, and machine learning models are trained to predict activities such as walking, sitting, and standing.

##  Dataset
- **Source:** Kaggle
- **Features:** Sensor data from accelerometers & gyroscopes
- **Labels:** Activities like walking, sitting, standing, etc.
- **Size:** Train and test sets with ~10,000+ instances

##  Technologies Used
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
- **Other models tested:** Random Forest (91.00%), GaussianNB (90.6%), Logistic Regression (89.58%).

# Model Performance Comparison

The table below presents the performance metrics of different classification models used for human activity recognition.

| Model                      | Accuracy | Precision | Recall  | F1-score |
|----------------------------|----------|------------|--------|----------|
| Support Vector Classifier  | 0.914489 | 0.915192   | 0.915227 | 0.913955 |
| RandomForestClassifier     | 0.910078 | 0.908959   | 0.907987 | 0.908312 |
| GaussianNB                 | 0.906006 | 0.907333   | 0.906015 | 0.906332 |
| LogisticRegression         | 0.896166 | 0.897162   | 0.897415 | 0.896103 |



##  Future Enhancements
- Try **Deep Learning** models (LSTMs, CNNs) for better accuracy.
- Experiment with **feature selection** techniques to improve performance.
- Real-time Prediction – Deploy for live activity recognition.
- Edge Optimization – Adapt for smartwatches & IoT devices.

