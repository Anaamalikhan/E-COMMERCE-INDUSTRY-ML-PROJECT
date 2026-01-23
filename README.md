# E Commerce Delivery Time Prediction Using Machine Learning

This project is a simple machine learning application developed for the e commerce industry. It predicts the estimated delivery time of an order using Linear Regression based on distance and number of packages. The project is designed for learning purposes and demonstrates the complete machine learning workflow.

---

## Project Description

The goal of this project is to estimate delivery time in hours for e commerce orders. The prediction is made using historical delivery data and a supervised learning algorithm called Linear Regression. The model learns the relationship between distance, number of packages, and delivery time.

---

## Topics Covered

Machine Learning Introduction
Supervised Learning
Linear Regression
Train Test Split
Model Evaluation Metrics
Mean Absolute Error
Mean Squared Error
Root Mean Squared Error
R Square Score

---

## Dataset Information

The dataset is created manually within the code for demonstration purposes. It contains the following columns.

Distance_km represents the distance of delivery in kilometers
Packages represents the number of packages in the order
DeliveryTime_hr represents the delivery time in hours

---

## Technologies Used

Python 3
Pandas
NumPy
Scikit Learn

---

## Machine Learning Workflow

Collect historical delivery data
Convert the data into a DataFrame
Select input features which are distance and packages
Select the target variable which is delivery time
Split the data into training and testing sets
Train the Linear Regression model using training data
Test the model using unseen test data
Evaluate the model using performance metrics
Predict delivery time for a new order

---

## Evaluation Metrics

Mean Absolute Error is used to measure average absolute difference between actual and predicted values
Mean Squared Error calculates the average squared difference between actual and predicted values
Root Mean Squared Error is the square root of Mean Squared Error
R Square Score measures how well the model explains the variance in the data

---

## Real Time Prediction

The model also supports real time prediction. A new order with distance and package count is provided as input and the trained model predicts the estimated delivery time in hours.

---

## How to Run the Project

Ensure Python 3 is installed on your system
Install required libraries using pip
Save the code file as delivery_time_prediction.py
Run the file using the Python command in terminal or command prompt

---

## Project Structure

delivery_time_prediction.py
README.md

---

## Future Enhancements

Use a larger real world dataset
Add more input features such as traffic and weather
Implement advanced regression algorithms
Deploy the model as a web application

---

## License

This project is intended for educational and learning purposes and is free to use.
