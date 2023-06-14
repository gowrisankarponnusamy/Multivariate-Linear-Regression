# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas

### Step2
import linear model

### Step3
read the csv file

### Step4
enter the parameters to implement

### Step5
run the prgram and predict the output

## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/cars (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predicted=regr.predict([[3300,1300]])
print("Predicted CO@ for the corresponding weight and volume",predicted)






```
## Output:
![image](https://github.com/gowrisankarponnusamy/Multivariate-Linear-Regression/assets/119393123/fee002e3-bf66-45f1-8ee4-7614c4b57105)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
