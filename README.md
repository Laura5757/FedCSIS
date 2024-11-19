# FedCSIS
Preliminary Score: 0.8161
Final Score: 0.8676
Submissions: 4
Place: 27/77

Process data:
Previewing the data (training and test) we see the that the delimiter is semi-colon and the decimal is a comma.
Then, for the data, we replace blanks and NA with nan in order to sustitute by the mean. 
For both data we will do this and then drop the columns 'Class' and 'Perform' to have the X set and we will only keep 'Class' columna to get y set.
Then extra processing using pipeline to standarise the data.

Parameters:
We used a dictionary to test some values for estimators, depth, simples split, simples leaf, we tried some large parameters to know a superior limit and then start decreasing the values. After this we got a limit of 49, 50, 51; 9, 10 , 11; 10, 11, 12; 1, 2, 3, respectively.  
Best parameters got: 9, 1, 11, 51

Training and predictions:
Finally, we store the best parameters in a variable and then use it for training, then prediction.
More info:
https://knowledgepit.ai/fedcsis-2024-challenge/
