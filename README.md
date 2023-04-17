# ML-Pima-Indians-Diabetes-Database
Predict the onset of diabetes based on diagnostic measures

## XGB
XGBoost (eXtreme Gradient Boosting) is a machine learning algorithm that is used for supervised learning tasks such as regression and classification. It is an implementation of the gradient boosting decision tree algorithm.

XGBoost is a popular algorithm due to its high performance and scalability, making it suitable for large-scale datasets. It works by building an ensemble of decision trees, where each tree is trained on the residual errors of the previous tree.

The algorithm uses a gradient descent approach to optimize the objective function, which is the sum of the loss function and a regularization term. The loss function is typically a measure of the difference between the predicted and actual values, and the regularization term is used to prevent overfitting.

XGBoost has several advanced features that make it stand out from other gradient boosting algorithms. For example, it uses a distributed computing framework to parallelize the training process, which can significantly reduce the training time. It also includes built-in handling of missing values, automatic feature selection, and early stopping to prevent overfitting.

XGBoost has achieved state-of-the-art results in many machine learning competitions and is widely used in industry for a variety of applications such as credit risk modeling, fraud detection, and image classification. It has also been successfully applied to non-tabular data such as text and images by adapting the algorithm to work with different types of input data.
## SVM
SVM stands for Support Vector Machine (SVM) with a linear or non-linear kernel. It is a supervised learning algorithm used for classification and regression analysis.

SVM is a popular algorithm because of its ability to perform well on a wide range of datasets, even when the number of features is larger than the number of samples. The goal of SVM is to find the hyperplane that best separates the two classes in the input space. The hyperplane is defined as the decision boundary between the classes, and the margin is the distance between the hyperplane and the closest data points of each class.

In the case of linearly separable data, a hyperplane can be easily found. However, in the case of non-linearly separable data, SVM uses a kernel trick to map the data into a higher-dimensional space where it becomes linearly separable. This allows SVM to classify complex datasets by transforming the data into a higher-dimensional space and then finding the optimal hyperplane in that space.

SVM uses a cost function to penalize misclassified data points and optimize the margin between the classes. The cost function balances the trade-off between maximizing the margin and minimizing the classification error.

SVM has several advantages such as the ability to handle high-dimensional data, handle non-linearly separable data using kernel trick, and have good generalization performance. It has been used in a wide range of applications such as image classification, text classification, and bioinformatics.

However, SVM can be computationally expensive for large datasets, and choosing the right kernel function and hyperparameters can be challenging.
