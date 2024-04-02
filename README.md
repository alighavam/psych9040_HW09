# Cosine Similarity

Cosine Similarity is defined as the cosine of the angle between two N dimensional vectors. Cosine function can take a value between -1 to 1. If two vectors are parallel and in the same direction (i.e. angle = 0), the cosine angle (cosine similarity) between the two vectors is $cos(0) = 1$. If two vectors are perpendicular, their cosine angle will be $cose(90) = 0$. 

So, for any given vectors A and B, the cosine similarity is defined as:

$$
    cos(\theta) = \frac{A.B}{\lVert A\rVert  \lVert B\rVert}
$$

# Solution:
In `Cosine_Similarity.ipynb` the cosine similarity is implemented using numpy (`cosine_similarity()`) and naive python and for loops (`cosine_similarity_naive()`). Additionally, the execution time of the two functions is compared (spoiler: numpy is ~4 times faster). 

Please use editors such as VS Code, online Google Colab, Conda Jupyter notebook or similar tools to open the `.ipynb` file and access the codes and results.