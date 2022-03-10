---
layout: single
title: Distance Measures
---
In this article, we will look into different distance measures we will use in Machine Learning. 

### 1. Euclidean Distance (L2):

Euclidean Distance is most frequently used distance measure. 

> ![Graph]({{"/assets/images/2021-04-04-distance-measures-1.jpg" | relative_url}})

If we observe the above picture, variable 'd' is called the Euclidean distance (L2). It is called the shortest distance from X1 to X2.

In above picture, we have two features, f1 and f2 and two datapoints in 2D, X1 and X2.

> ![Euclidean Measure]({{"/assets/images/2021-04-04-distance-measures-3.jpg" | relative_url}})


Euclidean distance can be formulated as 

> ![Euclidean Measure]({{"/assets/images/2021-04-04-distance-measures-2.jpg" | relative_url}})  

### 2. Manhattan Distance (L1):

Manhattan Distance is next frequently used and simple distance measure.

From above graph, Manhattan distance can be formulated as,

> ![Manhattan Measure]({{"/assets/images/2021-04-04-distance-measures-4.jpg" | relative_url}})

### 3. Minkowski Distance (LP):

Minkowski Distance is the generalized distance measure and can be formulated as, 

> ![Minkowski Measure]({{"/assets/images/2021-04-04-distance-measures-5.jpg" | relative_url}})

When p=1 in Minkowski Distance, it becomes *Manhattan Distance* and when p=2, it becomes *Euclidean distance*

Manhattan distance is also called as L1-Norm and Euclidean distance is called as L2-Norm

### 4. Hamming Distance:

Hamming distance is widely used in text processing and it gives us the # of difference of values between dimensions in vectors.
Hamming distance will  be used in Gene sequence.

> ![Hamming Distance]({{"/assets/images/2021-04-04-distance-measures-6.jpg" | relative_url}})

Above sequence generates value of 2 as there is difference of values in 7 and 10 dimensions


There are other measures as well and we will understand about few of them in the future. One such important and widely used measure is *Cosine Distance* and *Cosine similarity*, we will see this in upcoming articles.

### Bottomline:

There are many distance measures that are used in Machine Learning and few of them are Manhattan distance, Euclidean distance, Minkowski distance and Hamming distance. 
There are other distance measures also which are widely used and we will see them in future articles.

Hope you like this article and please share your feedback.