## For Data Exploration Notebook ##

# View Data #
Create visual to understand ratings distribution
Function to print out and test phrases before and after data cleaning
    input = sentence ID
    output = phrase

# Data Cleaning #
Remove first column
Remove non-alphabetical characters 
Remove stopwords

# Export Data #
Save and export data as a csv 


## For Model & Evaluation Notebook ##

# Imports #
Import libraries
Import cleaned training data
    Check data types of each column

# Build Classifier #
Set X = phrase
    Y = rating
Create tokenizer for reading phrases
    Based on maximum length of phrases in data set
Input tensor = X
Use summary() method to display output shape

# Train Classifier #
Train using model.fit()

# Test #
Import test csv


    
