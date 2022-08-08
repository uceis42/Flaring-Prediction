# Flaring-Prediction
This is the code and final dataset for the dissertation.

Model and result:

1. The Logistic Regression model can be found in model_only_LR.ipynb   
&nbsp;
2. The Logistic Regression model with Gradient Boosted Decision Tree can be found in model_GBDT_LR.ipynb  
    Correlation Table is also in the same notebook  
&nbsp;
3. The XGBoost model can be found in XGboost.ipynb   
    Predicted and Actual Flaring Gap Scatter Plot is also in the same notebook  
&nbsp;
4. The XGBoost model with filtered data can be found in XGboost-with 20 history.ipynb  
&nbsp;
5. The RNN model can be found in RNN_model.ipynb  
    Training and Validation Loss over Epochs chart is in the same notebook

Viz:

1. Flaring Scatter Plots are created in Viz_FT_Article.ipynb

2. The Impact of Well Vintage on Flaring (Monthly/Annually) are in  Viz_FT_Article.ipynb

3. The Relation Bar Chat of Flaring and Marker Dates is in Data_Exploration_v2.ipynb


Data processing:


1. The dataset for Logistic Regression is transformed from the orginal data in Merge_clean_df .ipynb

2. The dataset for both RNN and XGBoost is transformed from the orginal data in  Data transformation.ipynb
