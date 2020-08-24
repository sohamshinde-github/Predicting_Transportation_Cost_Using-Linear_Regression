### Predicting_Transportation_Cost_Using-Linear_Regression

1.This script predicts the transportation cost, which depends on the independent variables like distance travelled by truck, weight of load.
2.This was one of the problem solved in my Supply chain analytics course completed on Edx. The data was taken from the course.
https://www.edx.org/course/supply-chain-analytics


### Program Steps:
1. Imported libraries numpy, pandas, matplotlib, seaborn, sklearn
2. Read csv file in python 3
3. Analyzed the data and found that the distance and cost per load is highly related
4. Imported train_test_split from the sklearn.model_selection
5. Splitted data into training and testing data
6. From sklearn.linearmodel selected Linear Regression to perform linear regression
7. Fitted data by lm.fit() method
8. Predicted data with lm.predict() method
9. Plotted the graph with seaborn scatterplot and printed coefficients for distance, weight and time taken to get the parcel

