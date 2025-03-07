# 🚖 Taxi Cancellation Prediction using Neural Networks

## 📌 Project Overview

This project aims to predict taxi ride cancellations using machine learning and neural networks. The goal is to help **YourCabs.com** reduce cancellations and improve customer satisfaction.

## 📂 Dataset Overview
- **File**: `Taxi-cancellation-case.csv`
- **Size**: 10,000 rows, 17 columns
- **Features**: Customer ID, vehicle model, booking channel, travel type, geographic data, timestamps, etc.
- **Target Variable**: `cancellation` (0 = Not Cancelled, 1 = Cancelled)

## 📊 Exploratory Data Analysis (EDA)
- Visualized overall cancellation rate
- Examined feature distributions
- Identified relationships between key predictors and cancellations

## 🛠️ Data Cleaning & Feature Engineering
- Handled missing values
- Extracted useful features from timestamps (e.g., day of the week, time of day)
- Encoded categorical variables using one-hot encoding
- Normalized numerical features

## 🧠 Model: Neural Network Implementation
### **Architecture**
- **Input Layer**: Number of predictors
- **Hidden Layers**: 2 layers (32 neurons each, ReLU activation)
- **Output Layer**: Sigmoid activation (binary classification)

### **Training & Performance**
- Optimizer: `Adam`
- Loss Function: `Binary Crossentropy`
- Train-Test Split: `80-20`
- Epochs: `30`

### **Model Performance Metrics**
| Metric      | Score |
|------------|-------|
| Accuracy   | 85%   |
| Precision  | 0.78  |
| Recall     | 0.82  |
| F1 Score   | 0.80  |

## 📈 Visualizations
- **Confusion Matrix** (Shows true/false positives & negatives)
- **Training vs. Validation Loss** (Monitors overfitting)
- **Lift Curve** (Ranks prediction performance)

## 🔥 Key Insights & Recommendations
- **High-risk cancellation patterns** detected based on booking type and time of day.
- Suggest **driver incentives** for reducing cancellations during peak hours.
- Improve **booking system algorithms** to prioritize reliable drivers.

## 📌 Project Link
📂 GitHub Repository: (https://github.com/akash0820/taxi-cancellation-prediction)

## 📬 Contact
👤 **Akash Anand T**  
📧 akash.thiag@gmail.com
🔗 [GitHub](https://github.com/akash0820)
🔗 [LinkedIn](https://linkedin.com/in/akash081)



