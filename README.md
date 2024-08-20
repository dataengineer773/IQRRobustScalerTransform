We Use the robust scaler to the diabers daatset directly , we will use the defult configuration and scale values to the IQR First, a RobustScaler instance is defined with defult hyperparameters, Once defined we can call the fit_transform()
function and pass it to uor daatset to create a robust scale transformed version of our dataset and in the nest setpe we evaluate the same KNN model ans inside we use robust scaler transform of the dataset and in
the final we geta best result in accuracy in our model
