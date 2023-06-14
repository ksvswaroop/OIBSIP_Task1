IRIS Classifier Model

Understand the problem statement

As a Data Scientist,We all of us have the indepth knowledge of Iris Dataset.The Data Set contains 3 classes of 50 instances of each,where each class refers to species of iris flower.The main objective of the problem statement is to build a classifier model by using advance data science techniques.Here I am trying play with different algorithms and its parameters to maximize the accuracy of model.

Attribute Information:

Id----> Id represents each record uniquely(int)

SepalLengthCm---->Sepal lenght in centimeter(float)

SepalWidthCm---->Sepal Width in centimeter(float)

PetalLengthCm---->Peatal lenght in cm(float)

PetalWidthCm---->Petal width in cm(float)

Species----> Types of species of iris flower like setosa,versicolor,verginica(object)


Observations:

Using Petals over Sepal for training the data gives a much better accuracy. This was expected as we saw in the heatmap above that the correlation between the Sepal Width and Length was very low whereas the correlation between Petal Width and Length was very high. Thus we have just implemented some of the common Machine Learning. Since the dataset is small with very few features, I didn't cover some concepts as they would be relevant when we have many features.

I have compiled a notebook covering some advanced ML concepts using a larger dataset. Have a look at that tooo.

In above experiment,we have seen different accuracy with respect to different models like Logistic Regression,Decision Tree,Random Forest,XgBoost and KNN Among all of them KNN provide best accuracy for the small dataset.So I will consider KNN as my final model having train and test are 98% and 95%. As I mensioned I also play some hyperparameters for all models.
