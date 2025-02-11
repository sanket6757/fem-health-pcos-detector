Fem-Health: AI-Powered PCOS Detector
Overview:
Fem-Health PCOS Detector is an AI-driven diagnostic tool leveraging machine learning (ML) and deep learning (DL) models for early detection of Polycystic Ovary Syndrome (PCOS).
It processes medical datasets containing clinical, hormonal, and ultrasound parameters to provide probabilistic predictions.
📌 Methodology & Technical Approach
1️⃣ Data Collection & Preprocessing
Dataset: Includes patient records with features like BMI, insulin levels, LH/FSH ratio, menstrual irregularities, and ultrasound results.
Data Cleaning: Handling missing values using imputation techniques (mean/mode filling, KNN imputation).
Feature Engineering:
One-hot encoding for categorical variables.
Feature scaling using MinMaxScaler/StandardScaler.
Principal Component Analysis (PCA) for dimensionality reduction (if required).
2️⃣ Machine Learning Model Training
Algorithms Used:
Logistic Regression, Random Forest, XGBoost, SVM (Support Vector Machine) for initial classification.
Deep Learning (ANN/CNN-LSTM Hybrid Model) for advanced predictions.
Hyperparameter Tuning: GridSearchCV & RandomizedSearchCV for optimizing model performance.
Evaluation Metrics:
Accuracy, Precision, Recall, F1-Score, AUC-ROC Curve for performance assessment.
🔧 Tech Stack
Programming Languages: Python
ML/DL Libraries: TensorFlow, Keras, Scikit-Learn, XGBoost
Data Handling: Pandas, NumPy, OpenCV (for ultrasound image processing)
Visualization: Matplotlib, Seaborn, Plotly
Web/App Development: Flask, FastAPI, Streamlit, React
Deployment:  Firebase
