This is a machine learning model that trained to predict bulk modulus using Random Forest Regression
The data was sourced from Matminer's database
The data was then featurized to get the training & target values using conversion and density featurizers. 
The generated features are now used to train the Random Forest model.
The trained model was then cross validated for errors, and the Root Mean Square Error (RMSE) was evaluated
The model is visualized using Plotly to check the trends and identify outliers
To see the features that strongly influenced the model, Random Forest "feature importances" attribute was used
Lastly, Kernel Ridge Regression was used to train the same dataset, and the results were compared to that of Random Forest.
