# 🏠 California Housing Price Prediction — Deep Learning

This project predicts California housing prices using the California Housing dataset from `scikit-learn` and deep learning models built with TensorFlow & Keras. It showcases different model architectures, training strategies, and evaluation techniques.

## 📊 Features
- **Data Preprocessing**: Standardization with `StandardScaler`
- **Model Architectures**:
  - Sequential API
  - Functional API
- **Callbacks**:
  - ModelCheckpoint (save every epoch / save best model)
  - EarlyStopping
- **Model Persistence**:
  - Save & Load models in `.h5` format
- **Visualization**:
  - Training vs Validation Loss & MAE curves
- **Evaluation**:
  - Test set performance in real-world scale

## 📂 Dataset
- **Source**: [California Housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- **Target**: Median house value (in $100,000s)

## 🛠 Requirements
```bash
pip install tensorflow scikit-learn pandas numpy matplotlib
