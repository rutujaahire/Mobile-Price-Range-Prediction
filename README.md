# Mobile-Price-Range-Prediction

![image](https://user-images.githubusercontent.com/107872228/210802993-42150260-6e38-4ae7-bb48-3d53ca50525d.png)




Mobile phone has become a common commodity and usually the most common purchased item.
Thousands of types of mobiles are released every year with new features and new specification and new
designs. The studied dataset contains weather information which are the features (Temperature,
Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall),
the target is the number of bikes rented per hour and date information.


In this report, we train a model to predict the price range indicating how the high price is.The dataset
was obtained from the mobile phone marketing companies which contained what to understand the
sales data of mobile phones and factors which drive the prices.
First, we do Exploratory Data Analysis on the data set. We look for missing data values (none were
found) and outliers and appropriately modify them. We also perform correlation analysis to extract out
the important and relevant feature set and later perform feature engineering to modify few existing
columns and drop out irrelevant ones.


The developed model is then used to predict the price range of the new mobile phone. Three
machine learning algorithms namely Support Vector Machine (SVM), Random Forest Classifier
(RFC), Xtreme Gradient Boosting (XGBoost) are used to train the model and predict the output as
low, medium, high or very high. In order to improve the classification accuracy, Chi-Squared
based feature selection method is used. Among 21 features available in the dataset, only top 10
features namely RAM, pixel height, battery power, pixel width, mobile weight, internal memory,
screen width, talk time, front camera and screen height are selected and used to train the
model. Before applying feature selection, the accuracy obtained using SVM, RFC and XGBoost is
95%, 83% and 87% respectively.

After feature selection, the accuracy of SVM, RFC and XGBoost
improved to 97%, 87% and 92.3% respectively. From the experiments conducted, it is found that
SVM gave superior performance when compared to other two classifiers.


In this Prediction, Dataset is collected from the existing market and different algorithms are
applied to reduce the complexity and also identify the major selection features and get the best
comparison within the data . This Tool is used to find the best price with maximum
specifications.
