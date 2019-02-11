House Price Prediction

Using the Ames housing data, this system performs the following:
1. Predict the sale price or value of a house based on its fixed features
2. Predict the dollar impact should a renovation of a particular renovatable feature be carried out
3. Identify influencers or key properties of a house that highly result to an 'Abnormal' house sale. 

Results:
1. Obtained 89.65% accuracy on house price predictions based solely on fixed features.
2. 8.65% of the error from the house price predictions could be attributed to the renovatable features that were not considered.
3. $2500 dollar difference brought about by renovating the house exterior from Vinyl Siding to Brick Face
4. The Sale Type of 'Court Officer Deed' is the highest indicator of a house sale being classed as 'Abnormal', while a Sale Type of 'Brand New' is the highest indicator of a Sale Type being 'Non-Abnormal'

Single and Ensemble models such as Linear Regression, Decision Tree, K Nearest Neighbors, Random Forest, Stochastic Gradient Descent, and Extra Trees were some of the models used. 

Model tuning and feature selection techniques such as GridSearchCV, LassoCV, RFECV, and SelectKBest were also utilized.

