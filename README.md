# Journal-Week-12

## What I learned: December 14- December 18 edition

Week number 12, perhaps the last one?? Who knows...What we do know is that it’s here! This week, I mainly encountered different Machine Learning algorithms, so I’m going to do my best to explain them. I based my search of algorithms in one list of job opportunities in Data Science. The main ones were:

* k-Nearest Neighbors
The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. A classification problem has a discrete value as its output, while a regression problem has a real number (decimal point) as its output.

The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other. There are other ways of calculating distance, and one way might be preferable depending on the problem we are solving. However, the Euclidean distance is a popular and familiar choice. The algorithm is as it follows:
1. Load the data.
2. Initialize K to your chosen number of neighbors.
3. For each example in the data, calculate the distance between the query example and the current example from the data.
4. Add the distance and the index of the example to an ordered collection.
5. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances.
6. Pick the first K entries from the sorted collection.
7. Get the labels of the selected K entries.

The algorithm is simple and easy to implement, but it gets significantly slower as the number of examples and/or predictors/independent variables increase.

* Naive Bayes

Naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naïve) independence assumptions between the features. Naïve Bayes classifiers are highly scalable, requiring a number of parameters linear in the number of variables (features/predictors) in a learning problem. Maximum-likelihood training can be done by evaluating a closed-form expression, which takes linear time, rather than by expensive iterative approximation as used for many other types of classifiers. 

For some types of probability models, naive Bayes classifiers can be trained very efficiently in a supervised learning setting. In many practical applications, parameter estimation for naive Bayes models uses the method of maximum likelihood; in other words, one can work with the naive Bayes model without accepting Bayesian probability or using any Bayesian methods.

* Support Vector Machines (SVM)

Support vector machines are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis. Given a set of training examples, each marked as belonging to one of two categories, an SVM training algorithm builds a model that assigns new examples to one category or the other, making it a non-probabilistic binary linear classifier. An SVM maps training examples to points in space so as to maximise the width of the gap between the two categories. New examples are then mapped into that same space and predicted to belong to a category based on which side of the gap they fall.

Here you have it. As always, if you have any questions, just let me know!
