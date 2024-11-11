# Find_Default
Find credit card default
Objective: Build a classification model to predict fraudulent transactions using a credit card transaction dataset.  
Data Loading: Load the dataset, creditcard.csv, into a DataFrame.  
Exploratory Data Analysis:  
Visualize the distribution of feature V1 by class to understand data patterns.  
Data Cleaning: Drop the Time column, as it may not be relevant for classification.  
Feature-Target Split: Separate features (X) and target labels (y), where y indicates whether a transaction is fraudulent.  
Data Scaling: Use StandardScaler to scale features, ensuring consistent feature ranges for model training.  
Data Splitting: Split the data into training and test sets with an 80-20 ratio.  
Save Processed Data: Save the split datasets (X_train, X_test, y_train, and y_test) as CSV files for easy access and reuse.  
Model Selection: Choose a RandomForestClassifier as the baseline model.  

Hyperparameter Tuning:

Define a hyperparameter grid (e.g., n_estimators, max_depth, min_samples_split, and bootstrap).  
Perform randomized search with cross-validation (RandomizedSearchCV) to identify the best parameters.  
Model Training: Train the model with the best parameters obtained from the randomized search.  

Model Evaluation:  

Evaluate the model's accuracy on both the training and test sets.  
Print the accuracy scores to assess model performance.  
Model Saving: Save the trained best model using joblib for future use.  

Conclusion: Report on the model's accuracy and suitability for fraud detection.






