# Optimized Sentiment Classification using Numpy

A highly optimized version of Andrew Trask's Sentiment Classification from Deep Learning ND on Udacity

<br/>I have taken [Andrew Trask's](http://iamtrask.github.io/ "Andre Trask's") notebook on Sentiment Classification and have tried to _hyper optimize_ a number of routines following a set of two rules,  
1. Use _vectorization_ as much as possible 
2. Avoid _loops_ at all costs  

<br/>You would use such techniques in writing production ready code in Python. My optimizations are on an average 25% faster than the default solution, with _**over 250% (2.5x!) performance gain**_ in a few places.  

<br/>[![~2.5x performance improvement! ](https://github.com/pranjalchaubey/Optimized-Sentiment-Classification-using-Numpy/blob/master/img/optim1.png "~2.5x performance improvement! ")](https://github.com/pranjalchaubey/Optimized-Sentiment-Classification-using-Numpy/blob/master/img/optim1.png "~2.5x performance improvement! ")  

<br/>PS - I think Andrew Trask didn't use the complicated expressions in order to keep the whole tutorial beginner friendly - Kudos to him! 