# SVM

## Intuiton
Although SVMs have been gaining on popularity since the 1990s (especially today due to their application in machine learning) they were initially developed in the 60s.

SVMs are very powerful machine learning algorithms that let us separate observations both in a linear way and non-linear separable dimensions without the need of projecting them into a high dimension and back into a 2D dimension. This means that SVM help us to reduce computational costs and delays. Regardless if we have 2, 3, 10 or 100 variables, SVM helps us find the best decision boundary which help us separate our space into classes.

Conceptually it's actually a pretty simple algorithm but SVMs are slightly different from most machine learning algorithms. 

Using the apples and oranges analogy, we can explain the standard machine learning procedure one would apply for when you’re planning to teach a machine to differentiate between apples and oranges. First you would provide it some test data for the machine to analyze it and learn the features of either apples or oranges so that next time you it one of those two fruits, the machine can classify it as one of those two based on the parameters it previously learned from the test data.

Most of today’s known machine learning algorithms would look at the features that are the most stock standard characteristic ”apple” features for apples and the same for the oranges. 

In a 2D plane this stock standard apples or oranges would be at the center of their class or “cluster”. It is here where SVM differs from the rest. In most ML algorithms the machine would try to learn what an apple is from the stock standard apples and it would try to learn what an orange is from the most orange like oranges. Then the machine would be able to classify and come up with predictions when new data elements and variables are presented.

In the case of SVM, instead of looking at the most stock standard apples and oranges it kind of does the opposite, it looks at the extreme cases that are close to the boundary and it uses that information to construct the analysis. An SVM would look at the apples that are not the standard apple and eve have orange like features and the same for the oranges. By identifying those apples that look most like oranges and those oranges that look most like apples the algorithm is identifying the support vectors, those cases that are very close to the boundaries and help define where those boundaries are set. This means that SVM let’s us define where we differentiate apples from oranges and how far can an apple look like an orange while it’s still and apple and the same for oranges. 

This is what makes SVM unique and why it sometimes performs much better than non-supported vector machine algorithms.

Pros

Highl accuracy
Particularly effective on smaller/cleaner datasets

Cons

Long training times on larger data sets
Less effective with noisy data sets with overlapping classes 




## Dependencies

Numpy
Matplotlib
pandas


## How to run

### Import the libraries and the dataset

Preprocess accordingly

### Split dataset into training set and test set

Feature Scale the sets

```
Give an example
```

### And coding style tests

Explain what these tests test and why


### Fit the classifier to the training set

This is where configure the classifier parameters i.e. you can change the Kernel for different types of data


### Predict test results


### Draw the confusion Matrix

To determine the accuracy of the algorithm, it's a good idea to try other kernels to experiment with results and accuracy


### Visualize the results



## Resources

These are good sources for having a look further into the maths of SVMs

* [Standford CSS229 Lecture Notes (http://cs229.stanford.edu/notes/cs229-notes3.pdf/) - by Andrew NG
* [A Support Vector Machine in just a few Lines of Python Code](https://github.com/MaviccPRP/svm/blob/master/svm-primal.ipynb/) - A Support Vector Machine in just a few Lines of Python Code - by MaviccPRP

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
