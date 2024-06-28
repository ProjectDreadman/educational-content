# Getting Started with Machine Learning

## Introduction

Machine learning is a field of artificial intelligence that uses statistical techniques to give computers the ability to learn from data.

## Installation

1. Install Python and pip.
2. Install popular machine learning libraries: `numpy`, `pandas`, `scikit-learn`.

```sh
pip install numpy pandas scikit-learn
```
## First Machine Learning Model
Let's build a simple linear regression model.
```python
import numpy as np
import pandas as pd
from sklearn.linear_model import LinearRegression

# Sample data
X = np.array([[1], [2], [3], [4], [5]])
y = np.array([1, 3, 2, 3, 5])

# Create and train the model
model = LinearRegression()
model.fit(X, y)

# Make predictions
predictions = model.predict(X)
print(predictions)
```
## Conclusion
This is just the beginning. Explore the next tutorial to learn more about machine learning algorithms.

