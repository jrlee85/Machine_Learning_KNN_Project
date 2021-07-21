# machine-learning-knn-project
### UoL Machine Learning project to build a k-nearest-neighbours classifier from scratch

This project was created as part of my Data Science MSc. The task was to implement a KNN classifier with nested cross-validation, without using libraries such as Scikit-learn. 

I designed the classifier to use three different distance measurements: Euclidean, Manhattan, Chebyshev. Although not necessary for the assignment, I also included a tie breaker for scenarios where an equal number of neighbours suggested different classes. The tie breaker used the closest of the competing points to decide on the final classification.

Furthermore, the assignment only required a relatively simple nested cross-validation. I went beyond this and implemented a version which found the average scores of all k values and distances across each fold in order to select the best overall k-distance combination.

The project uses NumPy, Matplotlib, Pandas, and Scikit-Learn for checking results.
