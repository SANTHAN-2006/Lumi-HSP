# Lumi-HSP
Model used to predict the heart failure and heart stroke chances.

This Model has achieved an accuracy of  95%  during it's training process and can effectively be used for predictions.

# Model at a glance
This model is trained on "Kaggles's healthcare-dataset-stroke-data dataset" and "heart_failure_clinical_records_dataset".
The model is trained using "GradientBoosting" algorithm for the training process.

# Dependencies or Prequesites
Install Required Libraries:

1.Joblib library for saving the model.

2.Pandas. 

3.Scikit-learn.

# Instructions to use the model for predictions
1.Download the Model:
Download the model's file from the Latest release tag.

2.Load the Model:
load the model using the joblib.load() function from the joblib library. 
Provide the path to the downloaded model file as an argument.

Here's an example:


import joblib

#Load the model

model = joblib.load("path_to_final_model.pkl")




3.Prepare Input Data:

Make sure the Input data format is similar to the one's as mentioned above.
If not, Please make sure to preprocess the data to match it to the encoding of GradientBoosting algorithm.

4.Make Predictions:

You can call the predict() method on the loaded model and pass the preprocessed input data to get predictions.

For example:

#Prepare input data

input_data = ...  # Your input data here

#Make predictions

predictions = model.predict(input_data)

# Disclaimer
This model can predict the case with an accuracy of 95% but make sure you solely don't rely on this model for decisions.
In very few cases, the model can fail.
Pls consider the model's prediction just as an initial warning only!



