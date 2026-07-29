# ReneWind Predictive Maintenance using Neural Networks

## Project Overview

This project develops an Artificial Neural Network (ANN) model to predict failures in wind turbines using sensor data collected from turbines.

The objective is to help ReneWind proactively identify turbines that are likely to fail so maintenance can be scheduled before costly breakdowns occur.

---

## Business Problem

Wind turbines generate large volumes of sensor data. Unexpected failures lead to:

- Expensive repairs
- Production downtime
- Revenue loss
- Increased maintenance costs

Using historical operational data, this project builds a predictive model capable of identifying turbines at risk of failure.

---

## Dataset

The dataset contains operational measurements collected from wind turbines including multiple sensor readings and a binary target variable indicating turbine failure.

---

## Project Workflow

1. Data Exploration
2. Data Preprocessing
3. Missing Value Treatment
4. Feature Scaling
5. Train/Validation/Test Split
6. Artificial Neural Network Development
7. Model Optimization
8. Performance Evaluation
9. Business Recommendations

---

## Deep Learning Techniques

- TensorFlow / Keras
- Dense Neural Networks
- ReLU Activation
- Sigmoid Output Layer
- Adam Optimizer
- Batch Normalization
- Dropout Regularization
- Early Stopping

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

  
---

## Key Results

- Built multiple ANN architectures.
- Compared baseline and optimized neural network models.
- Improved recall for failure detection while maintaining high overall accuracy.
- Selected the best-performing model based on validation performance.
- Generated actionable maintenance recommendations.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

ReneWind-Neural-Network/

│── PreetiShankarSahu_NN_ReneWind.ipynb

│── README.md

│── images/

│     ├── data_distribution.png

│     ├── models_performance.png

│     ├── best_model_loss.png

---

## Business Impact

The predictive model helps:

- Reduce unplanned turbine failures
- Lower maintenance costs
- Improve turbine availability
- Increase renewable energy production
- Enable predictive maintenance strategies

---

## Data Distribution

![data_distribution](data_distribution.png)

## Models Performance

![models_performance](models_performance.png)

## Best Model Loss (HeNormal + BatchNormalization + Adam(lr=0.0005))

![best_model_loss](best_model_loss.png)


---

## Author

**Preeti Sahu**

Data Analytics | Machine Learning | Deep Learning | SQL | PySpark | Power BI
