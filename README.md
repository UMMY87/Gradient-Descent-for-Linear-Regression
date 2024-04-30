# Gradient-Descent-for-Linear-Regression
This code snippet showcases the implementation of gradient descent for linear regression in Python. It begins by defining the necessary functions for computing the cost, gradient, and performing gradient descent. The dataset consists of two arrays: `x_train`, representing the features (in this case, the size of houses), and `y_train`, representing the target values (house prices). The `compute_cost` function calculates the mean squared error between the predicted and actual values, while `compute_gradient` computes the gradients of the cost function with respect to the model parameters. The `gradient_descent` function iteratively updates the model parameters using the computed gradients to minimize the cost. 

After performing gradient descent, the code visualizes the cost function's convergence over iterations and predicts house prices for different sizes. Additionally, it displays contour plots illustrating the cost surface and the trajectory of parameter updates during gradient descent. Finally, it explores the effects of a large learning rate by visualizing divergence in the cost function. This code provides a comprehensive understanding of gradient descent's mechanics and its application in optimizing linear regression models for predicting house prices based on size.
## Cost-vs-w-with-gradient
![Cost-vs-w-with-gradient](https://github.com/UMMY87/Gradient-Descent-for-Linear-Regression/assets/117314436/2f479e4f-d74c-4d2b-aaee-13fed4a4f07b)
## Cost-vs-iterations-of-gradient-descent
![Cost-vs-iterations-of-gradient-descent](https://github.com/UMMY87/Gradient-Descent-for-Linear-Regression/assets/117314436/906baf77-1e31-4e8a-a355-272e9c990777)
## cost-over-iterations-on-contour-plot
![cost-over-iterations-on-contour-plot](https://github.com/UMMY87/Gradient-Descent-for-Linear-Regression/assets/117314436/7e6bb160-595c-4104-96a5-d86305642b9e)
## contour-plot-of-cost-vs-b,w-range
![contour-plot-of-cost-vs-b,w-range](https://github.com/UMMY87/Gradient-Descent-for-Linear-Regression/assets/117314436/48442c5e-6092-43a8-afc4-6a51b0785b8c)
## cost-vs-w-when-alpha-rate-too-large
![cost-vs-w-when-alpha-rate-too-large](https://github.com/UMMY87/Gradient-Descent-for-Linear-Regression/assets/117314436/fc6cf825-050a-4019-890e-7198db6ceb2f)
