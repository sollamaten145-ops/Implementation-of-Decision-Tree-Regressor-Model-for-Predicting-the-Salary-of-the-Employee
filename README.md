# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: Sastitha K
RegisterNumber: 212225230253

import pandas as pd
data=pd.read_csv("Salary.csv")
data.head()
data.info()
data.isnull().sum()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data["Position"]=le.fit_transform(data["Position"])
data.head()

x=data[["Position","Level"]]
x.head()
y=data["Salary"]
y.head()

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)

from sklearn.tree import DecisionTreeRegressor
dt=DecisionTreeRegressor()
dt.fit(x_train,y_train)
y_pred=dt.predict(x_test)
y_pred
from sklearn.metrics import r2_score
r2=r2_score(y_test,y_pred)

R2 score:  0.48611111111111116


dt.predict([[5,6]])

*/
```

## Output:
<img width="1025" height="322" alt="image" src="https://github.com/user-attachments/assets/3d51c305-1a93-4d48-9fbf-14ebfbb83d4d" />

<img width="480" height="243" alt="image" src="https://github.com/user-attachments/assets/22480172-cb32-4002-ac02-31220f001a76" />

<img width="536" height="161" alt="image" src="https://github.com/user-attachments/assets/858b6f40-a94b-46ca-9ba1-6329af3199bc" />

<img width="380" height="37" alt="image" src="https://github.com/user-attachments/assets/fce67bf8-6a7a-4b1b-a91e-49c5a29b7d2f" />

<img width="200" height="36" alt="image" src="https://github.com/user-attachments/assets/23475f64-6d64-4781-b224-89179a4fe126" />

## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
