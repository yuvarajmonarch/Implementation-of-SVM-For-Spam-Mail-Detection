# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
#### Step-1: Start.
#### Step-2: Import chardet.
#### Step-3: Read the dataset.
#### Step-4: Import SVC from sklearn.
#### Step-5: Fit the data in the model and run the algorithm.
#### Step-6: Stop.

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: YUVARAJ B
RegisterNumber:  212222040186

import pandas as pd
data=pd.read_csv("/content/spam.csv",encoding="Windows-1252")
from sklearn.model_selection import train_test_split
data
data.shape
x=data['v2'].values
y=data['v1'].values
x.shape
y.shape
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)
x_train
x_train.shape
from sklearn.feature_extraction.text import CountVectorizer
cv=CountVectorizer()
x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)
from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred
from sklearn.metrics import accuracy_score,confusion_matrix,classification_report
acc=accuracy_score(y_test,y_pred)
acc
con=confusion_matrix(y_test,y_pred)
print(con)
c1=classification_report(y_test,y_pred)
print(c1)


*/
```

## Output:

#### data
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/4c275760-0185-4ddc-9186-5748189d5945)


#### data.shape
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/c9d52168-14f9-4ada-a695-5df92bd5eccb)


#### x.shape
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/dabf1b76-0e67-42ab-a2ba-f4f4e94e2c48)

#### y.shape
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/be021b33-71d2-4d56-b32b-16394b6e6cc2)

#### x_train
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/b1eecc8c-261e-481d-9b13-62ea1de2be55)

#### x_train.shape
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/cd5fdc20-dde6-40ef-9423-65d3bd2aa274)

#### svc.fit(x_train,y_train)
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/96d3c8ed-b5c0-42e7-bb76-1f86b8ca9d75)

#### y_pred
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/e2a85b03-66d2-42bc-8113-327f7a311c42)

#### acc
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/9e270b41-3c09-459b-b545-d4563c6a8c42)

#### con
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/1bfde09a-80e3-4b8b-a15a-64bc12ce4be3)

#### c1
![image](https://github.com/yuvarajmonarch/Implementation-of-SVM-For-Spam-Mail-Detection/assets/122221735/d5be7c3a-6b96-479b-9183-ef78fa455d3a)




## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
