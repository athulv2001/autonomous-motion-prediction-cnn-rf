# autonomous-motion-prediction-cnn-rf
Predicting autonomous vehicle motion using CNN and Random Forest models on the Lyft Motion Prediction dataset.

# Autonomous Motion Prediction using CNN & Random Forest

This project predicts the motion of autonomous vehicles using a hybrid model that combines Convolutional Neural Networks (CNNs) for feature extraction and Random Forest classifiers for trajectory classification. It leverages the Lyft Motion Prediction dataset along with the L5Kit library for data handling and visualization.

## 🚗 Project Overview

Accurate motion prediction is essential for the safe operation of autonomous vehicles. This project integrates deep learning and ensemble learning techniques to predict future positions of vehicles in complex urban environments.

### 🔍 Objectives
- Extract spatiotemporal patterns using CNNs.
- Classify vehicle motion using Random Forest.
- Evaluate model performance with metrics like accuracy, F1-score, precision, and ROC-AUC.
- Improve reliability through feature engineering and data preprocessing.

## 📁 Dataset

**Source:** [Lyft Motion Prediction Dataset](https://self-driving.lyft.com/level5/data/)

- Contains data on agents, scenes, timestamps, and traffic light interactions.
- Preprocessed to handle missing values, normalize inputs, and engineer velocity/acceleration features.

## 🧠 Models Used

- **CNN:** Extracts motion-related spatial features from input frames.
- **Random Forest:** Classifies motion trajectories based on CNN features and engineered data.

## 📊 Evaluation Metrics

- Accuracy
- F1 Score
- Precision & Recall
- ROC-AUC
- Confusion Matrix

## 🧰 Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- L5Kit
- Pandas, NumPy, Matplotlib, Seaborn

## 📈 Results

- CNN achieved perfect accuracy on validation.
- Random Forest achieved ~96.5% F1-score.
- Robust predictions across various motion classes.

## 🏁 Future Work

- Incorporate Transformer architectures
- Real-time inference optimization
- Self-supervised pretraining
- Expand to pedestrian and cyclist motion


