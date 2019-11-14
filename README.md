# Happiness_Prediction
The python program deals with the predction of the happiness category based on the factors mentioned in the training and the test dataset.

# Step 1:
Once the test and train dataset is loaded and merged together . It is cleaned for
1. Missing or Null Values
2. The cleaned_hm row include the reviews which are analyzed of stop words, regular expression (checking for special characters, numeric values) and stemming.
3. Once the all the above is done then the reflection column and predict category column is converted to the numerical values.

# Step 2
The cleaned_hm column is then subjected to NLP method af creating count vectorizer and bag of words to extract the most recurring and important features from that cleaned_hm
Once this is done it is concatinated  reflection_period','num_sentence' column of the merged dataset.
Now the data is again splitted into the traing and testing data.

# Step 3
The last and final step is to apply the Machine Learning algorithm on the dataset to predict the category.
