# Bias and Variance

This is the central problem of Machine learning. Both Bias and Variance are properties of ML model in context. When one builds the model, these properties say how good .the model is for generalisation of the solution.

I wish not to make this too complicated to understand. In simple terms, Bias says how well your model fits the data and Variance talks about how susceptible is your model to changes in input data.

Keeping the above in mind, we can say low bias means model is closer to true understanding of the data and high bias means worst understanding. Similarly, low variance suggests the algorithm or the neural network architecture you have chosen will output similar model if you remove or add input data. And high variance means, model significantly differs with change in input data.

Ideally, we seek low-bias and low-variance models. But, it is almost always impossible. So, we try to strike a balance and this is called Bias-variance trade-off.

#### **Examples**

| **Algorithm** | **Examples** |
| :--- | :--- |
| Low-bias | Decision trees, kNN, SVM, non-linear algorithms. |
| High-bias | Linear and Logistics regression, Naive-Bayes, parametric models. |
| Low-Variance | Linear and Logistics regression, Naive-Bayes, parametric models. |
| High-Variance | Decision trees, kNN, SVM, non-linear algorithms. |

