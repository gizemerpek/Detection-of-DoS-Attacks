# Detection-of-DoS-Attacks
Detection of DoS Attacks Using HTTP Dataset
In this project, I focused on detecting DoS (Denial of Service) attacks using an HTTP dataset. The following steps were followed:

1. Data Exploration and Preprocessing
Examined the dataset in detail to identify missing or corrupted data.
Analyzed basic statistics and class distribution.
Investigated correlations in the dataset and eliminated unnecessary or low-impact features.

2. Feature Selection and Engineering
Used statistical and filtering methods to identify the most informative features.
Created new features to enhance model performance.

3. Traditional Machine Learning Models
Implemented the following four different machine learning algorithms:
Logistic Regression: Used as a baseline linear model.
Random Forest: Applied as an ensemble learning method.
XGBoost: Included as one of the boosting algorithms.
LightGBM: Utilized as a faster and optimized boosting method.

4. Deep Learning Models
Applied RNN (Recurrent Neural Network) to the dataset.
Used LSTM (Long Short-Term Memory) to capture long-term dependencies.
Implemented GRU (Gated Recurrent Unit) and compared it with RNN and LSTM.

5. Complex Neural Network Model (Ensemble Learning)
In the final stage, I designed a more complex neural network architecture combining CNN, LSTM, BiLSTM, and GRU to leverage different deep learning models' learning capabilities and achieve the best results.

6. Performance Evaluation
To evaluate each model's performance, the following metrics were used:

Accuracy
Precision
Recall
F1-Score
ROC AUC (Area Under the Curve)
Confusion Matrix
Loss and Accuracy Graphs

7. Conclusion and Learnings
Through this project:
I conducted a detailed Exploratory Data Analysis (EDA) to uncover key insights.
Understood the significant impact of feature selection and engineering on model performance.
Compared traditional machine learning and deep learning models, observing their respective advantages and disadvantages.
Discovered that ensemble models generally outperform individual models.

This study helped me understand how effective machine learning and deep learning techniques can be used to detect DoS attacks.
