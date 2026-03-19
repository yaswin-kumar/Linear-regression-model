Experience vs Salary Prediction 📈

This project implements a Linear Regression model from scratch to predict salary based on years of experience.

🚀 Features

- Built Linear Regression without using sklearn
- Implemented Gradient Descent
- Data Normalization (Min-Max Scaling)
- Prediction on new/unseen data
- Visualization of regression line

📊 Dataset

- Input: Years of Experience
- Output: Salary

🧠 Model Workflow

1. Normalizes input data
2. Train model using gradient descent
3. Predict salary for new values of the data
4. Plot regression line or best fitting one

💻 Example Usage

test_x = [10, 15, 5]

test_x_norm = (np.array(test_x) - x.min()) / (x.max() - x.min())

predictions = model.predict(test_x_norm)
print(predictions)

📈 Output

- Blue line → Actual data
- Red line → Predicted regression line

🔧 Requirements

- numpy
- matplotlib
- pandas


🎯 Learning Outcome

- Build an intuition behind the Linear Regression 
- Known the importance of normalization
- Model prediction on unseen data
-<img width="700" height="545" alt="Screenshot 2026-03-19 213017" src="https://github.com/user-attachments/assets/f735fbc4-859c-4f8f-a90d-a5dabe5a1f8f" />
The cost function/loss function decreases as iterations increasing accordingly in the above image
<img width="751" height="530" alt="Screenshot 2026-03-19 213643" src="https://github.com/user-attachments/assets/2a491f28-1c1b-4de4-a18c-09a966f65b76" />
The best Fitted line for the above data is as shown in the above image

