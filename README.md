# Machine-Learning-in-Iris-Dataset

In this code we will went through a full machine learning project made from scratch

So first We will make it ignore all the warnings

After that we will import the libraries and read the data from the iris.csv file and store it in a variable data
Then we will get and overview of data using data.head() this will give us the first 5 rows of the data and again python starts counting from 0
After that we will know what is inside the data like the data types, the type of the value each column and row contain then the type of the whole dataset which is taken as a a python pandas DataFrame and it's memory useage using the data.info()
Then we will describe the data using data.describe() it covers most of the statistics stuff like mean, standard deviation then basics math like min, 50% of the data, 25% of the data, 75% of the data maximum of the data and count.
After that we will get the total number of a specific Species (a column) from the iris dataset there are three values there, they are Iris-versicolor, Iris-virginica and Iris-setosa and it also gives the datatype of the number of a specific value in the column of Species and also the name for explaination and because of this python is easy and ml engineers love python. So there are 50 Iris-versicolor, 50 Iris-virginica and 50 Iris-setosa and 50's datatype is an integer so it is written as int64 integers are whole numbers like 0, 1, 55, 89 and all the number but not the decimal and fraction ones like 5.3 is not an integer so it means all whole numbers are integer even -1, -4, -5, -8 blablabla.
So after that we will remove the Id column from the data (it still exists in the dataset but python cannot) access it. and plotted the data and showed it
So after that we will make some violinplot using seabron and the y axis of the plot is Species and x is the columns from the data and our data is the data variable after removing the Id.
Then we will make our training data X and y, in X we have removed the Id and Species from the data and in y we have the Species column from the data and after that we will get the shape of the data for X it is (150, 4) which means it has 4 columns and 150 rows while it is (150,) for y so it means y has 150 rows with 1 column
After that we will experiment it KNearestNeighbors algorithm with different n values and plot the accuracy_score of the model (accuracy_score for sklearn / scikit-learn and accuracy for tensorflow) with a ylabel of Accuracy Score, xlabel of Value if k FOR KNN (K-Nearest-Neighbors) and title of Accuracy Scores for values of k of k-Nearest-Neighbors
After that we will predict it with the LogisticRegression Algorithm and fit the model with our training data (X and y) and then make a variable y_pred which and predict X inside the y_pred variable and then print the accuracy_score of y and y_pred
Now we will declare the variables of X_train, X_test, y_train, y_test which will contain the train and test split of X and y
So now we will again experiment KNearestNeighbors with different n values but now we will not predict the X now we will predict the X_test and merge the accuracy score of y_test and y_pred in a list called scores and plot it
Now we are gonna again predict it with the Logistic Regression but now it is different we will fit X_train and y_train and predict X_test in a variable called y_pred  and then we will print the accuracy_score of y_test and y_pred
Now it is our last step we again use the KNearestNeighbor algorithm here with a n_neighbor value of 12 and fit the X and y with the KNearestNeighbor Algorithm and predict it with 6, 3, 4, 2 and we are finished!

If you find any problem you can gmail me at asarkar310@gmail.com. Bye! :D
