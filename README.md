# Ridge-and-lasso

Ridge and Lasso Regularisation Methods:   

L1 Method - Lasso  
L2 Method - Ridge   

While exploring Linear Regression in Python, I got the accuracy rate of 67% using Train-Test-Split.   

For dataset, I have used the internal dataset of Boston. The data was already clean and normal, so, I directly build the model.  

To improve the accuracy, first I have used Ridge Method. To chose the value of alpha, I have used GridSearchCV.  I got the error rate, by using Mean Squared Error as 29% (approx)   

Then, I used the Lasso Method, where I got the error rate as 34% (approx).   

Even though the error rate for Ridge is less, we will go ahead with Lasso Method because Lasso will help us in Feature Engineering.   

Lasso will shrink the less important important feature’s coefficient to zero, thus removing some features altogether.   

It will give us a better stable model with Low Variance. 
