# 🚀 Dynamic Pricing Engine

A machine learning-based dynamic pricing application that predicts optimal product prices using demand, inventory, competitor pricing, and seasonal factors.

## 📌 Project Overview

The **Dynamic Pricing Engine** is a machine learning project designed to help businesses make data-driven pricing decisions. It analyzes relevant pricing factors and generates a predicted optimal price based on the input provided by the user.

The application provides an interactive interface built with Streamlit, allowing users to enter pricing parameters and view predictions.

## ✨ Features

* 📊 Predict optimal prices using a trained machine learning model.
* 📦 Consider inventory levels and customer demand.
* 🏷️ Incorporate competitor pricing into predictions.
* 🌦️ Account for seasonal factors.
* 🖥️ Provide an interactive web interface using Streamlit.
* 🤖 Support data-driven pricing decisions.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Web Framework:** Streamlit
* **Data Processing:** Pandas
* **Machine Learning:** Scikit-learn and other libraries used in the project
* **Model Storage:** Pickle (`.pkl`)
* **Development Environment:** Visual Studio Code
* **Version Control:** Git and GitHub

## 📂 Project Structure

```text
dynamic-pricing-engine/
├── data/
│   └── pricing_data.csv
├── model/
│   ├── pricing_model.pkl
│   ├── timeseries_model.pkl
│   └── xgboost_model.pkl
├── reinforcement_learning/
├── time_series/
├── app.py
├── app_backup.py
├── train_model.py
├── train_rl.py
├── train_timeseries.py
├── train_xgboost.py
├── pricing_environment.py
├── requirements.txt
└── README.md
```

*Note: The structure above is illustrative. Update it to match the actual files in your repository.*

## ⚙️ Installation and Setup

### Prerequisites

* Python 3.10 or another version compatible with the project's dependencies
* Git
* pip

### 1. Clone the repository

```bash
git clone https://github.com/mohammedzamaanyousuf60-spec/dynamic-pricing-engine.git
```

### 2. Navigate to the project directory

```bash
cd dynamic-pricing-engine
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python -m streamlit run app.py
```

The application should open in your browser. If it does not, visit:

`http://localhost:8501`

## 🧪 How to Use

1. Launch the Streamlit application.
2. Enter the current price.
3. Provide the demand value.
4. Enter the available inventory.
5. Specify the competitor's price.
6. Set the seasonal factor.
7. Click **Predict Optimal Price**.
8. Review the predicted price displayed by the application.

## 🎯 Project Objectives

* Explore machine learning techniques for dynamic pricing.
* Understand how demand and inventory can influence pricing decisions.
* Incorporate competitor prices and seasonal variations into price prediction.
* Build an interactive application that demonstrates machine learning predictions.
* Gain practical experience in Python, data processing, model training, and application development.

## 🔮 Future Enhancements

* Deploy the application to a public cloud platform.
* Improve model performance through systematic evaluation.
* Add historical price trends and interactive visualizations.
* Integrate real-time market and competitor pricing data.
* Develop a pricing recommendation dashboard for business users.
* Compare different machine learning models using appropriate evaluation metrics.

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes. Predictions depend on the training data, model design, and input values. The predicted price should not be treated as a guaranteed optimal market price.

## 👨‍💻 Author

**Mohammed Zamaan Yousuf**

GitHub: [@mohammedzamaanyousuf60-spec](https://github.com/mohammedzamaanyousuf60-spec)

---

⭐ If you find this project interesting, consider giving the repository a star!
