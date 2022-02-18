# ML_Automation

"Problem 1: Web Scrapping"

Solution File: Filmography.py

Additional Comments:
I've used BeautifulSoup to perform the web automation task.
This program will give you list of all the filmography in descending order.
I've fetched this infpo from Wikipedia.

Alternate Approach: I can also Use imdb api, which can also provide me all th necessary details but thats not automation.



"Problem 2: ML Algorithm"

Solution File: Kepler_Intern.ipynb

Additional Comments:

As mentioned in the Assignemnt, we have to classify koi_disposition, and its a Multi Class Classification Problem.
Sub Questions:

1.Why did you choose the particular algorithm?
Ans: I've choosed DecisionTreeClassifer as it gives me the best accuracy among other classifiers, and it is great for Multi-Class Classification with many features.

2.What are the different tuning methods used for the algorithm?
Ans: I've used RandomizedSearchCV to get the best parameters. I can also use GridSearchCV.

3.Did you consider any other choice of algorithm?Why or why not?
Ans: I considered SVM, and KNN too, those also are great for multi class classification, and the acuracy is also similar.

4.What is the accuracy?
Ans: I got an accuracy of 86.1% with a precision of 89.6%. This accuracy can be further improved by Feature Selection or using a DL Model with appropiate time.

5.What are the different types of metrics that can be used to evaluate the model?
Ans: I've used accuracy, precision score, recall score and f1_score. We can draw an ROC Curve for the same.
