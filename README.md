MLP 7  - Machine Learning mines news headlines in order to predict stocks.

Industry
Finance | Stocks | Investment 

Skills
Python | NLP | Sentiment analysis | Data visualizations | Data manipulation

Problem statements
Predict whether the stock market trend will have a net increase or decrease based on news headlines.

Data Description
Top 25 global viral news headlines from 2000 to 2016
Label 0 means net decrease in stock market trend and label 1 means net increase in stock market trend. 

Methods
Split training and test data
Remove punctuation
Lower case all headlines 
Combine all headlines in one strong
Use bag of words method and rerank based on frequency
Train model
Use random forest algorithm 
Test model metrics for accuracy, presion, F1-score, and recall

Results 
139 true positives
47 false positives
13 false negatives 
179 true negatives 
model correctly predicted about 84.13% of the labels in the test dataset
for class 0, out of all the predicted positive labels, 91% were actually positive. 
for class 0, model correctly identified 75% of the positive samples. 
for class 0, The F1-score is 0.82 (82%)
for class 1, predicted negative labels, 79% were actually negative. 
for class 1, model correctly identified 93% of the negative samples. 
for class 1, F1-score is 0.86 (86%), providing a balanced measure.

Conclusion 
Accuracy of 84.13%
For class 0, the model achieves great  precision and  F1-score 
model performs reasonably well in identifying the positive samples of class 0
there is room for improvement for recall for class 0
For class 1, the model achieves great  recall and F1-score 
model appears to perform well in identifying the negative samples of class 1
there may be some scope for improvement in precision for class 1


