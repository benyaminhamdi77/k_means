# K-Means Project

A practical example for k-means clustering

## Introduction

You can see the code of the k-means algorithm in an optimal form while Manhattan and Euclid functions are used in it.

## Code

To view the code, you can download it and access its contents. 

A part of the code that the Manhattan function and Euclid were interviewed can also be seen in the lower part. 

```python
def euclidean_distance(p1, p2):
    return np.sqrt(np.sum((p1 - p2) ** 2))

def manhattan_distance(p1, p2):
    return np.sum(np.abs(p1 - p2))