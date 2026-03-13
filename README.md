# FUTURE_ML_01
This project focuses on predicting future sales using past business data. By analyzing trends and seasonal patterns with machine learning, the model helps businesses plan inventory, manage cash flow, and make smarter decisions to avoid overstocking or shortages.
📊 Sales Forecasting using Machine Learning

📌 Project Overview

This project builds a sales forecasting system using historical retail data from the Superstore dataset. The goal is to predict future sales by analyzing past order information such as date, quantity, and discount.

By applying Machine Learning, the project helps demonstrate how businesses can use data to predict demand, plan inventory, and improve decision-making.

🎯 Objective

The main objective of this project is to predict future sales based on historical data.

This project focuses on:

Preparing time-based features from order dates

Understanding sales trends

Training a Machine Learning model

Comparing actual vs predicted sales

📂 Dataset

The dataset used is Sample Superstore Dataset, which contains historical retail transaction data.

Important features used in this project:

Order Date

Quantity

Discount

Sales

Additional features were created from the order date:

Year

Month

Day

Day of Week

⚙️ Technologies & Libraries

This project was built using:

Python

Pandas – Data processing

NumPy – Numerical operations

Matplotlib – Data visualization

Scikit-learn – Machine Learning

🧠 Machine Learning Approach
1️⃣ Data Preprocessing

Loaded the dataset using Pandas

Converted Order Date to datetime format

Created time-based features:

Year

Month

Day

Day of week

2️⃣ Feature Selection

Features used for training:

day
day_of_week
month
year
Quantity
Discount

Target variable:

Sales
3️⃣ Train-Test Split

The dataset was split into:

80% Training Data

20% Testing Data

shuffle=False was used to maintain time order.

4️⃣ Machine Learning Model

A Pipeline was created using:

StandardScaler → Feature scaling

LinearRegression → Prediction model

Pipeline improves workflow by combining preprocessing and modeling.

📈 Model Evaluation

Two evaluation metrics were used:

Mean Absolute Error (MAE)

Measures the average difference between predicted and actual sales.

R² Score

Shows how well the model explains the variation in sales data.

📊 Visualization

The project includes a visualization comparing:

Actual Sales

Predicted Sales

This helps understand how well the model forecasts future demand.

The plot displays the sales trend comparison over time.

▶️ How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/yourusername/sales-forecasting-project.git

2️⃣ Install Required Libraries

pip install pandas numpy matplotlib scikit-learn

3️⃣ Run the Python Script

python sales_forecasting.py

📌 Future Improvements

This project can be improved by:

Using advanced models like ARIMA, Prophet, or LSTM

Adding feature engineering for seasonality

Building an interactive dashboard

Deploying the model using Streamlit or Flask

👨‍💻 Author

Abhinav Tripathi
B.Tech CSE (AI) – Future University Bareilly
Machine Learning Enthusiast

🔗 LinkedIn
https://www.linkedin.com/in/abhinav-tripathi-a02b16334

🔗 GitHub
https://github.com/Abhinav8640

