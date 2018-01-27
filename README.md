
## 1. The domain of the problem
We can use the Iris data set to develop a supervised learning model to predict the class of a new Iris flower that we come across.
The Iris data set consists of 3 classes of 50 instances each, where each class refers to a type of iris plant. Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. Two among the three species were collected in Gape Peninsula all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus. 
## 2. A problem statement 
The purpose is to analyze Iris flowers and we want to develop a model that will be able to tell us the class of a newly found iris. 
Basically the model inputs are column 1-4 (Sepal.Length, Sepal.Width, Petal.Length and Petal.Width) and it will output a class column 5 (Species). The data set is presented in our R analysis notebook. 
## 3. Data set Description
The size of the data set is 150 rows and 5 columns.The data set consumes memory of about 7.01 Kb.
The data types are numeric for the columns 1-4 and factor for column 5.The first 4 columns are the features (input to the model) and the 5th column is what we are looking for (the classification of the iris). 
We measured the minimum value, maximum value, median value, mean value like below

![summarystats](https://user-images.githubusercontent.com/35319815/35469395-b3b9cd86-0301-11e8-943f-c756e2ccb5d0.JPG)

The distribution of the target class of the features are as below represented with the histogram.
![sepal length](https://user-images.githubusercontent.com/35319815/35469599-0d2e9f64-0306-11e8-84ef-f9fbfcab5cca.JPG)

![sepa width](https://user-images.githubusercontent.com/35319815/35469610-65f972d6-0306-11e8-976d-d9973a29c310.JPG)

![petal length](https://user-images.githubusercontent.com/35319815/35469611-6d5b50d0-0306-11e8-9029-db1e8396d9d8.JPG)

![petal width](https://user-images.githubusercontent.com/35319815/35469614-717731f2-0306-11e8-931c-d51a142c369a.JPG)

## 4. A proposed solution
We would propose a solution of 3 different algorithms to see which gives us the most accurate results - LDA, KNN, and CART.
## 5. A benchmark model
We will break the measurements into 80/20 percent. We use the 80 percent of the data set to create the models and we test the models against the other 20%. We need to test or validate our models for benchmarks, so we use only 120 rows to come up with the models and then we test the models against the other 30 rows to see how accurate they are.
## 6. A performance Metric
 We use the ratio of the correct predictions of the model divided by total number of instances in the data set.

