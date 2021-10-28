# Optimize-ML-modeling-using-a-timing-decorator

First, I wrote a timing decorator to measure the function execution time. Then, I found the length of a list and wrote a code for printing the execution time which substracts the
starting time and ending time. I also measured the time taken to compute matrix multiplation from two given numpy arrays. Subsequently, I wrote a compact loop with the function 
and observed how execution time varies with input size. It can be seen clearly that with the increase in sample sizes, the execution time also increases. After testing all this, I  
added ML estimator from scikit learn into the timing-estimator decorator which decorated a scoring function that fitted the data and returned the accuracy_score. I will make some synthethic 
data and initialized a logistic regression estimator. With the classifier_accuracy function, I get both the execution time and the accuracy score. 
Later, I modified the data and recorded execution time and played with the estimator to optimize the cost performance. Then, I plotted the optimized model, and I found that we should
16 trees for the model.
