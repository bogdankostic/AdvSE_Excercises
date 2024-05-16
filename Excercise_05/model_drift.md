# Examples for Model Drift

## Concept Drift
A spam detection model is trained on a dataset where spam emails typically contain certain keywords. 
Over time, spammers change their tactics because their mails get classified as spam, using different language and
structures to bypass the spam filters. As a result, the model's accuracy decreases because the underlying 
relationship between content of the mail and the classification of being spam or not spam changes.
 
## Data Drift
A credit scoring model is trained on data from a period of economic stability. During a period of economic instability, 
the distribution of features such as income, employment status, and loan amounts in new data changes significantly. 
The model's performance decreases because it was not trained on data representing these new conditions.

## Label Drift
A sentiment analysis model is trained on social media posts where positive and negative sentiments are labeled 
according to certain criteria. Over time, the criteria for labeling sentiment changes, due to shifts 
in cultural context, semantic meaning and connotation fo certain words. This results in a different distribution of
labels for the same kind of input data, causing the model to misclassify sentiments.

## Feature Drift
A weather prediction model is trained using features like temperature, humidity, and wind speed to predict rain. 
Over time, due to climate change, the patterns of these weather features change. For example, higher humidity becomes 
more common and more linked to storms. The model's performance gets worse because the importance of these features has 
shifted due to the new weather conditions.

## Seasonal Drift
A sales forecasting model is trained on retail sales data that includes seasonal patterns, such as increased sales 
during the holiday season. If the model is applied to data from a different season without considering these patterns, 
its predictions will likely be not accurate. For example, predicting December sales based on data from summer months 
without adjusting for seasonal effects can lead to significant errors.
