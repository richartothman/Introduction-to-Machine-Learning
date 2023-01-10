# Introduction-to-Machine-Learning
## Final Project

### Brief introduction
A company has just completed a large testing study for different product prototypes. And we are asked to use this data to build a model that predicts product failures.
Here implemented a machine learning pipeline to train a classification model on the training data set. But before doing this and after reading a couple of discussions in the kaggle community, the trick is in preprocessing the data to get a more higher/accurate result. In my case, I first handle the missing values and categorical values by using KNNImputer and Labelencoder respectively. This is then split into train and validation datasets using k fold cross validation method with 5 numbers of splits as there are 5 product codes. For the model, I used Logistic regression with my custom hyperparameters that I played around with and stuck with the one I did my highest score with.
### How to run
1. Download model.joblib
2. Download 109550199_Final_inference.ipynb
3. Change the test dataset path and output csv file path
6. Run or execute the ipynb file and will result in a csv file being created

###My environment
I used google colab to run my code.
