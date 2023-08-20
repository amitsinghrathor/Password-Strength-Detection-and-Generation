# password_strength_prediction
Predicted the strength of password using NLP and ML ,using a dataset from Kaggle.<br  />
To avoid Parse Error i used error_bad_lines=False.<br  />
We have two columns password and strength.<br  />
Values in strength column are 0,1,2 .<br  />
0 being the least safe,1 is safer and 2 is the safest password.<br  />
Categorised the data into dependent and independent variables.<br  />
I used TfidfVectorizer from feature_extraction.text to convert text to numbers. <br  />
Then created Train-Test-Split.<br  />
By using few ML algorithms like Logistic regression,Multinomial Naive bayes etc.<br  />
I will predict whether a password falls in category 0,1 or 2.
