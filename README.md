# MSCS_634_Lab_2_
Explanation

The Wine dataset from sklearn contains chemical properties of wines classified into three categories. Before applying machine learning models, the dataset must be explored and split into training and testing sets.

Results and Observations

KNN Observations
•	Lower values of k (like 1) may lead to overfitting. 
•	Moderate values (such as 5 or 11) usually provide better accuracy. 
•	Higher k values may smooth decision boundaries but reduce sensitivity. 
RNN Observations

•	Small radius values may result in very few neighbors, reducing accuracy. 
•	Large radius values include more points but may introduce noise. 
•	Performance is highly sensitive to feature scaling and radius choice.
Comparison of KNN and RNN

Aspect	KNN	RNN
Neighbor selection	Fixed number (k)	Based on distance (radius)
Stability	More stable	Can be unstable
Parameter tuning	Easier	More sensitive
Performance	Generally consistent	Varies significantly
