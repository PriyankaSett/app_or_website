# app_or_website



The dataset can be found at : https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website


About Dataset
This dataset is having data of customers who buys clothes online. The store offers in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website.


# Summary of this project : 

For this dataset, the aim is to find/predict that whether the app or the website will return good revenues to the business. For this the basic data exploration is done using conventional methods. Being a regression problem, multicollinearity was checked and features were selected in usual manner. Also outliers have been taken care of.

The conclusion is one should go with the app.

This conclusion was obtained and verified after looking at the heatmap, feature importance, removing the outliers.

After all these several models were used to predict the outcomes. The training and testing accuracy has been also studied along with the r2 score and adjusted r2 score as metric. The predictions for test data and the residuals were also studied. It was found that simple linear model is overpredicting the test data. Random Forest Regressor works best for this data.


