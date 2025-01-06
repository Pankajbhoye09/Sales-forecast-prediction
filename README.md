# Sales Forecasting with Linear Regression

This project demonstrates how to forecast monthly sales using a Linear Regression model. 

**Project Goal:**  To predict future monthly sales based on historical sales data. This involves building a model that learns from past sales trends to make informed predictions about future sales performance.

**Approach:**

1. **Data Preparation and Feature Engineering:**
   - Load monthly sales data.
   - Calculate the difference in sales between consecutive months.
   - Prepare the data for supervised learning by creating lagged features (using past months' sales to predict the next month).
   - Split the data into training and testing sets.

2. **Scaling:**
   - Scale the data using Min-Max scaling to improve model performance.

3. **Model Training and Prediction:**
   - Train a Linear Regression model on the training data.
   - Make predictions on the test data.

4. **Model Evaluation:**
   - Evaluate the model using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score. These metrics help understand how well the model's predictions match the actual sales values.

5. **Visualization:**
   - Plot the actual sales versus the predicted sales for visual comparison. This helps in understanding the model's accuracy and identifying any potential areas for improvement.
