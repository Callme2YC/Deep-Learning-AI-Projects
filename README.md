# Deep Learning Projects

## Project 1: Predicting Customer Churn using Feed-Forward Neural Networks

### Overview
This project focuses on predicting customer churn using feed-forward neural networks. Accurately forecasting churn enables businesses to proactively address customer retention, enhancing profitability and competitive advantage.

### Dataset
- **Source:** [Kaggle Churn Modeling Dataset](https://www.kaggle.com/datasets/shubh0799/churn-modelling/data)
- **Size:** 10,000 instances with 14 features

### Methodology
- Data preprocessing: Removal of irrelevant variables, one-hot encoding for categorical variables, and feature normalization.
- Model architecture: Simple feed-forward neural network with two hidden layers of 64 neurons each, using ReLU activation.
- Training: Used PyTorch with a learning rate of 0.01, batch size of 32, and the Adam optimizer.

### Results
- Accuracy: 82%
- Precision: 53%
- Recall: 66%
- F1 Score: 0.73

### Conclusion
The model effectively predicts customer churn with a balanced precision-recall trade-off. Future improvements include enhancing the model's architecture and incorporating regularization techniques.

---

## Project 2: Multi-task Learning for Predicting House Prices and House Category

### Overview
This project develops a multi-task learning model to simultaneously predict house prices and categorize houses into distinct categories. The model leverages shared and unique patterns across regression and classification tasks for improved generalization.

### Dataset
- **Source:** "House Prices - Advanced Regression Techniques" dataset
- **Features:** 80 attributes including numerical and categorical data

### Methodology
- Data preprocessing: Addressed missing values, feature engineering, categorical variable encoding, and data normalization.
- Model architecture: Shared bottom layer with task-specific top layers for regression (house prices) and classification (house categories).
- Training: Utilized PyTorch Lightning, incorporating advanced features like logging, model checkpointing, and early stopping.

### Results
- Regression:
  - Mean Squared Error (MSE): 0.1549
  - Mean Absolute Error (MAE): 0.234
- Classification:
  - Accuracy: 88%
  - F1 Score: High across most categories

### Conclusion
The model demonstrates robust predictive capabilities in both regression and classification tasks. Future work will focus on addressing class imbalances and refining feature relationships to further improve performance.

---

Feel free to check out the detailed reports and code in the respective project repositories.
