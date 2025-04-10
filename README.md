Overview
  The prupose of this exercise was to use a deep learning machine learning technique in google colab to analyze data. The  goal was to analyze the data with techniques we covered in class and see if the given dataset could be used to achieve an accuracy over 75% by dropping columns, increasing hidden layers or adding columns back.

  

*   The variablethis model targets is "IS SUCCESSFUL"
*   features of this model are: NAME	APPLICATION_TYPE	CLASSIFICATION	USE_CASE 	ORGANIZATION	INCOME_AMT	ASK_AMT
*   EIN, SPECIAL_CONSIDERATIONS, STATUS, AFFILIATION can all be dropped because they do not provide useful information to train our model
*   I selected 80 layer 1 nodes using RELU, 30 layer 2 nodes wusing RELU and an output layer with 30 nodes and a signmoid model.
*   I was able to get close however google colab kept crashing due to a lack of VRAM after I started optimizing. I tried 4 different methods dropping additional columns but it still crashed
*   I was attempting to drop columns that did not represent diverse data as it would not add value to the model training

Summary
  The results of the process were sub par and I Was not able to reach the desired accuracy. I am not sure why it could not calculate the model. I believe a random forest model would suit this data better because of the categories present in the dataset. Using multiple decision trees would yield better results for this data.
