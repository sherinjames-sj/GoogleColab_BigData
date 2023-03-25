# GoogleColab_BigData
# About Coursework
# Big Data Analytics [CN7031] CRWK 2022-23
# GoogleColab_BigData/ID142_CN7031.ipynb

The code aims to perform a machine learning classification task on the CSE-CIC-IDS2018 dataset, which contains network traffic data, to determine whether the traffic is malicious or not. A little over 6.4 GB in size, the dataset has 80 attributes. Only about 2.34 GB of the data will be used, though, due to the machine's limited computing power. The "Label" column, which distinguishes between malicious and benign traffic, is the most crucial column in the dataset.

The code starts by importing the necessary libraries, including Pandas, NumPy, and Scikit-learn. The data is then read from the CSV file and preprocessed, with unnecessary columns being removed, missing values being handled, and categorical variables being converted to numerical values. The data is then divided into training and testing sets.

The next step is to choose the best machine learning algorithm for the classification task. The Random Forest algorithm, an ensemble learning technique that builds multiple decision trees and combines their outputs to make predictions, is used in this instance by the code. The algorithm is tested on the testing set after being trained on the training set using various metrics like accuracy, precision, recall, and F1 score.

The code then saves the trained model to a file so that it can be used later to make predictions on new data. Overall, the code illustrates how to perform a machine learning classification task on a sizable dataset and emphasizes the significance of preprocessing and choosing the right algorithm for the task.
