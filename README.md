# Problem-1-Data-Science-Challenge_IISC_Banglore
First downloaded the dataset and read the csv file into dataframe
Started Visualizing the features and from the question we know that director_name,genre,title_year are most important.
So dropped some columns which are not important for the prediction
Did feature engineering. Added new features into the dataframe 
Perfomed One-Hot-Encoding on the column "genres"
Perfomed Label Encoding on the column "director_name" so that the categorical variables are converted to numerical for better evaluation of model.
So here we have 2 predictions to make 
1 Predicts  the release year of his next movie when director name given(regression problem)
2 predicts the genres of his next movie when director name given(classification problem)
I have used random forest regressor and random forest classifier to predict 
For the regression problem calculated "Mean Absolute Error","Mean Squared Error","R-squared"
For the classification problem calculated "accuracy","precision","F1-Score","Recall"
