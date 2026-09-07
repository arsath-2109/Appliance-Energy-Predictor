# Appliance Energy Consumption Prediction

## 📌 Project Overview

This project uses **Simple Linear Regression** to predict appliance energy consumption based on temperature. The model is developed using Python and Scikit-learn and evaluates its performance using Mean Squared Error (MSE) and R² Score.

## 🎯 Objective

To predict **Energy Consumption (kWh)** using **Temperature (°C)** as the independent variable.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib

## 📂 Dataset

The project uses the `appliance_energy.csv` dataset.

### Features

* **Temperature (°C)** – Independent variable

### Target

* **Energy Consumption (kWh)** – Dependent variable

## ⚙️ Methodology

1. Import the required Python libraries.
2. Load the appliance energy dataset.
3. Check and remove missing values.
4. Select temperature as the input feature.
5. Select energy consumption as the target variable.
6. Split the dataset into training and testing sets using an 80:20 ratio.
7. Train a Simple Linear Regression model.
8. Predict energy consumption for the test data.
9. Evaluate the model using MSE and R² Score.
10. Visualize the actual data and regression line.
11. Save the trained model using Joblib.

## 📊 Model

The project uses **Simple Linear Regression** to establish the relationship between temperature and appliance energy consumption.

## 📈 Model Evaluation

The model performance is evaluated using:

* **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted values.
* **R² Score:** Measures how well the model explains the variation in energy consumption.

The actual MSE and R² values depend on the dataset used.

## 📉 Visualization

The project generates a scatter plot showing the test data along with the fitted regression line.

## 💾 Saved Model

The trained model is saved as:

`appliance_energy_model.pkl`

The saved model can be loaded later using Joblib without retraining the model.

## 🚀 How to Run

### 1. Install required libraries

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

### 2. Place the dataset

Keep `appliance_energy.csv` in the required project directory.

### 3. Run the Python/Google Colab code

Execute the code cells to train, evaluate, visualize, and save the model.

## 📁 Project Structure

```text
Appliance-Energy-Prediction/
│
├── appliance_energy.csv
├── appliance_energy_model.pkl
├── appliance_energy_prediction.ipynb
└── README.md
```

## 🔮 Future Improvements

* Use multiple features such as humidity, appliance type, and operating time.
* Compare Linear Regression with other machine learning algorithms.
* Improve prediction accuracy through feature engineering.
* Deploy the model as a web application or API.

## 👨‍💻 Author

**S. Mohammed Arsath**
Mechanical Engineering Student
