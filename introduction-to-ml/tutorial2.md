# Basic Machine Learning Algorithms

## Supervised Learning

Supervised learning algorithms are trained using labeled data. Examples include linear regression, logistic regression, and decision trees.

```python
# Linear Regression
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X, y)
predictions = model.predict(X)
```
## Unsupervised Learning
Unsupervised learning algorithms are used to find patterns in data without labels. Examples include k-means clustering and principal component analysis.
```python
# K-Means Clustering
from sklearn.cluster import KMeans

model = KMeans(n_clusters=3)
model.fit(X)
labels = model.labels_
```
## Conclusion
With these basic algorithms, you can start building simple machine learning models. Keep practicing and explore more advanced algorithms.
