https://regressiondeploy-m8geb5599bhrcqztvsxv3q.streamlit.app/


# 📊 Insurance Prediction using Logistic Regression

A simple and interactive **Machine Learning web application** built with **Streamlit** that predicts whether a person is likely to purchase life insurance based on their age using **Logistic Regression**.

The application also visualizes the dataset, displays model performance, and demonstrates how the sigmoid function converts predictions into probabilities.

---

## 🚀 Demo Features

- 📂 Load and display insurance dataset
- 📈 Visualize Age vs Insurance Purchase
- 🤖 Train a Logistic Regression model
- 🎯 Predict insurance purchase for any age
- 📊 Display prediction probability
- ✅ Show model accuracy
- 🧮 Manual Sigmoid Function calculation
- 🎨 Interactive Streamlit interface

---

## 📁 Project Structure

```
Life-Insurance-Prediction/
│
├── app.py                  # Streamlit application
├── insurance_data.csv      # Dataset
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

## 📚 Dataset

The dataset contains two columns:

| Feature | Description |
|----------|-------------|
| Age | Age of the person |
| Bought_Insurance | 1 = Purchased Insurance, 0 = Did Not Purchase |

---

## 🧠 Machine Learning Model

The project uses **Logistic Regression**, a supervised machine learning algorithm used for binary classification problems.

### Why Logistic Regression?

Since the output has only two possible classes:

- Bought Insurance (1)
- Didn't Buy Insurance (0)

Logistic Regression is an ideal choice because it predicts probabilities using the **Sigmoid Function**.

---

## 📈 Sigmoid Function

The probability is calculated using:

```
P = 1 / (1 + e^(-z))
```

where

```
z = (Coefficient × Age) + Intercept
```

The app also performs this calculation manually to demonstrate how Logistic Regression works internally.

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Matplotlib
- NumPy

---

## 📸 Application Preview

The application includes:

- Interactive dashboard
- Dataset viewer
- Scatter plot visualization
- Model accuracy display
- Prediction interface
- Probability estimation
- Sigmoid calculation

---

## 🎯 Learning Objectives

This project helps understand:

- Binary Classification
- Logistic Regression
- Train-Test Split
- Probability Prediction
- Sigmoid Function
- Model Evaluation
- Streamlit Deployment

---

## 👩‍💻 Author

**Anushka Singh**

AI & Machine Learning Enthusiast

---

## ⭐ If you found this project helpful, don't forget to star the repository!
```
