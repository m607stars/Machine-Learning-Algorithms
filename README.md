# Machine Learning Algorithms
This repository contains some of the very famous Machine Learning algorithms built from scratch, i.e. without using the sklearn library, or others like Pytorch, Tensorflow, etc. Each algorithm has been implemented from scratch along with explanation for each and every step. Also, in the end there is comparison by using libraries. Sometimes, the results are not so good as it has not been optimized, but the main motive was the implementation. The algorithms have been explained in brief too in the ipynb file. 

## 1.Linear Regression 
Linear regression has been performed on the height-weight dataset. It is a very small dataset containing only 15 data points. The trained ML model then shows us the expected height for a given weight or can be made to do the reverse operation too. 

## 2. Logistic Regression
Logistic Regression has been performed on the very famous Iris flower dataset. The dataset consists of some of the features of the Iris flower like Sepal-length, width, etc. and 3 species of the flower. For simplicity, the algorithm implemented from scratch uses only one feature, i.e. sepalwidth. Still, the accuracy and the graph show that the results are pretty much good. 

## 3. Support Vector Machines (SVMs)
Here, I have tried to make a SVM classifier, using only linear kernel for simplicity. The from scratch part requires some knowledge of mathematics behind the SVMs whcih has also been shown in the ipynb file. Cvxopt library has been used for qp solver (Quadratic programming solver). Although the accuracy is not upto the mark, the ipynb file presents the beautiful world of SVMs. This classifier has also been trained on the Iris dataset, and for simplicity uses only two features. 

## 4. Decision Trees 
Here, I have worked with another famous, red wine dataset and tried to classify the wine as per its quality with the help of decision trees. The wine quality is decided as True or False on the basis of 4 most relative parameters according to the analysis. 

# Built with 

* <a href="https://scikit-learn.org/stable/">skLearn</a>
* <a href="https://pandas.pydata.org/" >Pandas</a>
* <a href="https://numpy.org/" >Numpy</a>
* <a href="https://matplotlib.org/" >Matplotlib</a>
* <a href="http://cvxopt.org/" >Cvxopt</a>

# Acknowledgements
* <a href="https://www.kaggle.com/andonians/random-linear-regression">Dataset</a>
* <a href="https://www.youtube.com/watch?v=kHwlB_j7Hkc&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=4">Linear Regression Algorith Explanation</a>
* <a href="https://medium.com/python-in-plain-english/introducing-python-package-cvxopt-implementing-svm-from-scratch-dc40dda1da1f"> Medium blog for SVMs using cvxopt</a>
* <a href="https://medium.com/@smlra_kjsce/supporting-svms-support-vector-machines-bf5bfba88a0b">SMLRA Blog - SVM Maths</a>
* <a href="https://medium.com/@smlra_kjsce/vectorized-view-of-svms-6a85dae8ca72">SMLRA Blog - SVM Intuitions</a>
* <a href="https://www.youtube.com/watch?v=7VeUPuFGJHk"> Youtube lecture for decision trees</a>
* <a href="https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009">Red wine dataset</a>
* <a href="https://machinelearningmastery.com/implement-decision-tree-algorithm-scratch-python/">Decision Trees blog for implementation</a>
* <a href="">Decision trees blog</a>
