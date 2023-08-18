# Lumi-HSP: Heart Failure and Stroke Prediction Model
Model used to predict the heart failure and heart stroke chances.

This Model has achieved an accuracy of  95%  during it's training process and can effectively be used for predictions.

# Model at a glance
This model is trained on "Kaggles's healthcare-dataset-stroke-data dataset" and "heart_failure_clinical_records_dataset".
The model is trained using "GradientBoosting" algorithm for the training process.

# Model Highlights

Accuracy : 95%

Install Required Libraries:

1.Joblib library for saving the model.

2.Pandas. 

3.Scikit-learn.

# Getting Started

# Instructions to use the model for predictions
1. **Download the Model**:
 
Download the model's file from the Latest release tag.

2. **Load the Model**:
 
load the model using the joblib.load() function from the joblib library. 
Provide the path to the downloaded model file as an argument.

Here's an example:


import joblib

#Load the model

model = joblib.load("path_to_final_model.pkl")




3. **Prepare Input Data**:

Make sure the Input data format is similar to the one's as mentioned in above Images (data format 1, data format 2).

If not, Please make sure to preprocess your data to match it to the encoding of GradientBoosting algorithm.

4. **Make Predictions**:

You can call the predict() method on the loaded model and pass the preprocessed input data to get predictions.

For example:

#Prepare input data

input_data = ...  # Your input data here

#Make predictions

predictions = model.predict(input_data)

# Disclaimer
While the Lumi-HSP model boasts a high accuracy rate of 95%, it's essential to use its predictions as an initial warning rather than a definitive diagnosis. Relying solely on the model may not be advisable, as there are instances where it could yield incorrect results. Always consult a medical professional for accurate health assessments.

# Contributor
This project was developed by Santhan Kumar and is provided as-is under the GNU General Public License v3.0


By using Lumi-HSP, you're tapping into advanced predictive capabilities. Remember, health decisions should be made with care and consultation with medical experts. Enjoy the benefits of data-driven insights while prioritizing your well-being.
