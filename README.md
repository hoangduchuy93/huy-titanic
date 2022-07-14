![image](https://user-images.githubusercontent.com/91864024/178941919-10f00880-de1f-4452-98f3-7926a0c1bdbf.png)
# Prediction of surviving passengers on the Titanic
## I. Outline
- This prediction system is built based on a dataset in a competition on Kaggle (https://www.kaggle.com/competitions/titanic/data)
- The demo app is implemented on Heroku, available for your experience: https://huy-titanic.herokuapp.com/
## II. Problem
- Titanic is a steam-powered super ship that has gone in maritime history 
because of the accident that happened to it and the mysteries associated with it.
- Titanic was known globally for its enormous size and luxury. It was considered an unsinkable supership before it hit an iceberg and 
sank to the bottom of the North Atlantic Ocean
- Although it may be by luck or by chance, survivors may have more common traits that aid their survival than others.
- In this project, model try to predict the possibility of a passenger that could survive based on their characteristics (name, age, gender, room, ...)
## III. Project implementation
### 1. Problem Understanding
Based on the above description => identify the problem:
- Build a prediction model to help predict the survivors based on given dataset
- Proposed models: logistics regression

![image](https://user-images.githubusercontent.com/91864024/178957566-c6bf0f52-99f9-49f0-91ff-762eaa690db7.png)
### 2. Data Understanding/ Acquire
There are 3 files (csv format) that contained:
1. gender_submission.csv: contains PassengerId and Survived (0/1)
2. train.csv, test.csv: data for training and testing your model
- survival:	survival (0 = No, 1 = Yes)
- pclass: ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- sex:	sex	
- Age:	age in years	
- sibsp: number of siblings / spouses aboard the Titanic	
- parch: number of parents / children aboard the Titanic	
- ticket:	ticket number	
- fare:	passenger fare	
- cabin: cabin number	
- embarked:	port of embarkation	(C = Cherbourg, Q = Queenstown, S = Southampton)
### 3. Build model
The steps to build model are:
- Read and understand the data
- Clean the data
- Prepare the data for modelling
- Modelling applied logistics regression to make prediction
- Final analysis and commit if the model can work well
### 4. User interface
You can connect to the demo app (https://huy-titanic.herokuapp.com/) for your experience. Below image show welcome screen:
![image](https://user-images.githubusercontent.com/91864024/178959653-9afdfd41-f779-46cd-b1e0-39678b95a010.png)
#### 4.1. Overview
- By default, you will enter to Overview. You can choose your mode by choosing different function inside the drop-box on the left
- As you enter to the application, you will see the explanation of data using to predict. This part will be same as welcome screen.
#### 4.2. Build Project
- In this part, you can see some rows of data, training/testing score, confusion matrix and visulization for the result.
- Some photos from this part are as following:
![image](https://user-images.githubusercontent.com/91864024/178960902-1ecf5393-ec89-41d7-b4f7-0d0f3c76f3a4.png)
![image](https://user-images.githubusercontent.com/91864024/178961028-eeafb9dc-e4a4-45f0-9787-5b90987faaed.png)
#### 4.3. New Prediction
- This model allows you to input a passenger information and predict their possibility of survivor.
- For example, passenger information as following will have 99% of survivor
![image](https://user-images.githubusercontent.com/91864024/178961616-99994794-17d2-4bbd-822b-826df2fd9f6a.png)
### 5. Conclusion
- Model can predict the possibility of survivor for passengers with accuracy 81%
- You can also input new data for prediction.

Thank you for your experience with my application. Hope you enjoy it!






