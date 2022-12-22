# NLP-project-for-tweets

In this project, the tweets regarding the accidents or news related to natural disasters are classfied using the Kaggle dataset. The first implementation is done in "Text_processing" file in which the sentences are tokenized/split and assigned the unique number (categorical features). This text processing method converts the textual data or unstructured data to structured data or numerics. This helps for the machine learning algorithm application. 

In the second step, the machine learning algorithm "Logistic_regression_model" is implemented. Using the GridSearchCV model, around 70 percent accuracy score was obtained for the training dataset. Then the best model is implemented on the test dataset. 

Similarly, different models are implemented to obtain better accuracy of the training dataset. The training and test datasets are labelled as "train.csv" and "test.csv" files. The full routine is done on Jupyter Notebook and Python. 

The below image shows the sample of training tweets. Here "1" represents the accident or natural disaster news/tweets and "0" is for false tweets.
<img width="884" alt="training_data" src="https://user-images.githubusercontent.com/50884851/209160801-08a8a5f6-4c26-456d-8d9f-7563854a749f.png">
