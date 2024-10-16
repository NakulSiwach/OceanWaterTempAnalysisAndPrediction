# OceanWaterTempAnalysisAndPrediction
Ocean water temperature prediction with CalCOFI dataset and temp vs salinity analysis

EDA :
  correlation heatmap
  individual barplots
  scatter wrt R_temp
  
Preprocessing :
  removing categorical (needs a check of whether it's good practice)
  removing columns with more than 20% NULL
  removing every row with R_temp as NULL
  Scaling (min-max)
  Normalisation
  
Model Builing :
  Build MLR model from scratch
  Regularisation (will add soon)

Performance evaluation :
  Accuracy
  R2 score
  MSE
