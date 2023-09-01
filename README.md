# CODSOFT

Load the Titanic dataset.
Perform data preprocessing:
Fill missing 'Age' values with the median age.
Fill missing 'Fare' values with the median fare.
Drop the 'Cabin' column due to a large number of missing values.
Encode the 'Sex' column using label encoding.
Create a new 'IsFemale' feature.
Drop irrelevant columns ('Name', 'Ticket', 'Embarked', 'Sex').
Split the data into training and testing sets.
Create a random forest classifier model and train it on the training data.
Make predictions on the test set and calculate accuracy.
Create a prediction DataFrame with 'PassengerId' and predicted 'Survived' values.
Generate missing 'PassengerId' values for the passengers with missing IDs.
Create a new feature 'IsFemale' for the missing passenger IDs based on the existing 'IsFemale' column.
Reorder the columns in the 'missing_features_df' to match the training data.
Predict survival using the missing features.
Update the 'PassengerId' column with the predicted values.
Concatenate the data back together.
Sort the DataFrame by 'PassengerId'.
Save the updated DataFrame to a CSV file.
