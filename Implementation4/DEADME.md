#Implementation 4
unsupervised learning  
***
##Part1 kmeans  
Data size is 2059\*477, of course the label size is 2059\*1.
>randomRuns = 10  
>>initiate k centers with random samples  
>>start interation
>>>step 1: find nearest cluster center for each of the n data point  
>>>step 2: update the centers  
>>>step 3: return `cluster` and `SSE`  

>choose the best SSE and best cluster  
>assign each cluster(and all its instances) a class label based on the majority ground truth class  
>mesure the purity(accuracy)  