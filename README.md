Project Summary: Customer Churn Prediction
Introduction
The objective of this project was to develop a predictive model for customer churn using a given training dataset, while the test dataset lacked churn labels. The approach encompassed thorough data preprocessing, feature engineering, model selection, and evaluation to optimize predictive accuracy and model efficiency.

Data Preprocessing
Initial Analysis:

Verified the integrity of the combined training and test datasets, excluding the churn column in the test set.
Examined data types and distribution of each column to identify necessary transformations.
Data Type Conversion:

Converted certain columns to float32, as precision beyond this level was unnecessary for the project’s predictive needs. This also demonstrated the potential for a storage-efficient model.
Feature Correlation and Engineering:

Computed the correlation matrix between each feature and the churn label to identify and exclude irrelevant features.
Applied feature mean normalization where applicable to ensure consistent scale and distribution, enhancing model performance.
Model Selection and Training
Initial Model Testing:

Tested a decision tree model, suitable for binary classification tasks. The model exhibited a high ROC score on the training set but underperformed on the validation set due to data imbalance.
Addressing Data Imbalance:

Re-trained the model with a balanced dataset, equalizing positive and negative examples. This adjustment reduced bias and improved validation performance.
Advanced Model Exploration:

Evaluated various models, including TensorFlow neural networks and advanced decision tree techniques like XGBoost.
Employed rigorous feature engineering, data normalization, and hyperparameter tuning to enhance model accuracy.

Results
The final model, a fine-tuned TensorFlow neural network, demonstrated superior performance with approximately 75% accuracy.
Noted that predicting customer churn with absolute certainty is inherently challenging due to the complexity of human behavior. However, model performance can be further enhanced by collecting additional features and expanding the dataset.
Conclusion
The project successfully developed a predictive model for customer churn with significant accuracy improvements through methodical data preprocessing, feature engineering, and model optimization. The process highlighted the importance of addressing data imbalance and the potential of deep learning techniques when fine-tuned appropriately.
