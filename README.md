# NLP Assessment
Task 

## Problem Statement

### Abstract: 
Research and make an NLP pipeline to classify search query to various predefined classes.

### Description: 
NLP model should classify search query consisting of keywords (examples mentioned in list below) and assign them relevant class labels.

### Predefined classes:
[Sports, Tech, General Knowledge, Historical, Politics, Informative, Automotive, Literature]

1. The predefined classes are not absolute and exhaustive and classes can be added to make tags more accurate. 
2. Note: A high level tag/label is required for this problem and detailed tags about classes are not required. eg sports tag is sufficient for all sports seperate tags should not be given like cricket or football.
3. For a query multiple tags can be also be predicted but they should be highly relevant and there confidence scrore should be displayed.
4. Any dataset can be used to train model.
5. If using pretrained models details should be given why that model is selected and its metrics.
6. A none tag can be assigned to topics which do not have very high confidence score.
 
### Sample Output:
User query - Predicted class tag

1. Indian Cricket team - Sports
2. Data Structure and Algorithm - Tech
3. Cars - Automotive, Sports
4. Hydroelectricity - Informative
5. Steve Jobs - General Knowledge, Tech.
6. Pen is mightier than the sword - Literature


### Submission:
1. Colab notebook showing implementation of the model with predictions.
2. Appropriate comments and clean code should be submitted in notebook.
3. Mentioning the relevant links and references used in pipeline would be appreciated.
