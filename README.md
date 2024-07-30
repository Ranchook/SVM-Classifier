# SVM-Classifier
4th Class project - training a SVM classifier on multi-dimensional dataset

Support Vector Machine (SVM) is a powerful supervised learning algorithm used for classification and regression tasks. It works by finding the hyperplane that best separates the data into classes, maximizing the margin between the closest data points of each class, known as support vectors. SVM is effective in high-dimensional spaces and can handle linear and non-linear classification by using kernel functions to transform the input data into a higher-dimensional space.

In this exercise we were asked to train the classifier on 'Faces' dataset, we also examined the influence of 2 main parameters of a SVM classifier - the degree of the polynomial kernel function and the regularization parameter, on the accuracy of the train and test dataset. After checking both parameters, we chose the optimal values to run them both together.

## The exercise
1. Train the classifier on 'faces' data and measure the accuracy.
    
    a. Load the data and split it 80% for train, 20% for test.
    
    b. Train the classifier, use: 
                                    from sklearn.svm import SVC
                                    svc = SVC(kernel='poly', degree = 2, C = 0.1) # example values
    
    c. What is the train and test datasets accuracies?
    
    d. What are the confusion matrixes of the train and test datasets?  
    
    
2. Test the influence of the different parameters on the classifier's performance, use cross validation:

    a. Degree of the polynomial kernel function (set by the parameter degree)
    
    b. The regularization parameter (set by th parameter c)
#### Make sure to plot the results.


3. Based on your results, choose the optimal values to set the parameters and explain why these are the optimal values.
