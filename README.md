# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the required libraries.
2.Upload and read the dataset.
3.Check for any null values using the isnull() function.
4.From sklearn.tree import DecisionTreeClassifier and use criterion as entropy.
5.Find the accuracy of the model and predict the required values by importing the required module from sklearn.

## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by:   BALA MURUGAN
RegisterNumber:  212222230017
*/
```
```
/*
import pandas as pd
data=pd.read_csv("/content/Employee.csv")

print('data.info:')
data.info()

print('data.isnull().sum():')
data.isnull().sum()

print('value_count: ')
data["left"].value_counts()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()

data["salary"]=le.fit_transform(data["salary"])
data.head()

*x=data[["satisfaction_level","last_evaluation","number_project","average_montly_hours","time_spend_company","Work_accident","promotion_last_5years","salary"]]
x.head()**

y=data["left"]

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=100)

from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier(criterion="entropy")
dt.fit(x_train,y_train)
y_pred=dt.predict(x_test)

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy

dt.predict([[0.5,0.8,9,260,6,0,1,2]])
*/
```
## Output:
![decision tree classifier model](sam.png)
![240619390-b27f0bee-6257-4551-99d1-ec9dc11f19f6](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/8fe068f8-7330-43e2-999b-f2ee87b036d9)

![240619527-b37c53e3-2ac3-4dd7-a91b-981f246230ff](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/d05ae24c-0b61-46b3-89a7-32a32ecfeb6c)

![240619703-4a33723e-f708-4b6e-8859-86e7f29301d6](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/0d379b27-198d-4998-be56-4778a0183e1d)


![240619808-7cd8e1df-21b7-4f4f-873f-467bc651f1bf](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/73522303-fc1a-4620-ba31-11fad5ab275c)

![240619931-802acc2e-7ef8-4cab-a65a-30cd1e2d8817](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/2bae8f3c-e06c-472a-b6cc-17577486c946)

![240620142-4a95c659-c93b-4ca1-8337-b3738dc760d2](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/4692e978-ac5e-4b80-b6c2-d53426d3d3b9)

![240620256-36c020fb-42e6-4570-8952-6a2200c4beb6](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/8c7e5dc3-68f0-4619-a411-5d4d12cdc0a4)

![240620359-a5d7faa3-6fc4-4c07-844a-720dfab0bacd](https://github.com/Bala1511/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/118680410/5ff2ddb2-79e8-47a8-af33-7078435ba583)

## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
