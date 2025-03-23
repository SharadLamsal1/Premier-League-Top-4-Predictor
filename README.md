# Premier League Top 4 Predictor - Logistic Regression
This model takes input of total points obtained in season and tries to predict whether that team will finish top 4 and qualify for champions league or not. I collected sample data from past 5 seasons and created a logistic regression model from scratch without the use of library.

##Steps

### Data Collection: 
Sample data is manually collected, where X_train represents the number of points and Y_train indicates whether a team finished in the top 4 (1) or not (0).

### Data Visualization: 
The data is visualized using scatter plots to understand the distribution of points and top 4 finishes.

### Sigmoid Function: 
A sigmoid function is implemented to map predictions to probabilities.

### Cost Function: 
The cost function for logistic regression is defined to measure the error between predicted and actual values.

### Gradient Descent: 
Gradient descent is used to optimize the model parameters (weights and bias) by minimizing the cost function.

### Model Training: 
The model is trained using the gradient descent algorithm, and the cost is monitored over iterations.

### Prediction: 
The trained model is used to predict whether a team will finish in the top 4 based on the input points.

### Evaluation: 
The training accuracy and final cost are calculated to evaluate the model's performance.

![image](https://github.com/user-attachments/assets/3dc6279a-a3d8-45d0-b872-26b34402a45d)
