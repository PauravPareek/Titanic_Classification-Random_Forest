# Titanic_Classification-Random_Forest
titanic classification using random forest 

This git is just normal representation of classic titanic classification, Please find details below.
https://www.kaggle.com/c/titanic
Data set is availaible on kaggle home page.

Classifier = Random Forest

Language = Python 3 

Current accuracy after kcross = 79.46%


Note: ** in code represent work needed on that particular part of kernel.


ToDo List:

**1 = need to perform data wrangling and check partial dependency b/w each Independent Vetor vs Dependent vector, 
          and then drop less important classes currently just assuming Name, Ticket, Fare & Cabin are not contributing in survival

**2 = Treating train and split both right now, no need to treat test data, occures in overfitting

**3 = Treating missing values in train and split both right now, no need to treat test data, occures in overfitting 

**4 = Filling all age missging values (177values out of 890 = 19.88%) zero, which is not efficient enough. 
          need to follow an approach for filling age according to name or by anyother mean, Check top kaggle submission to get an idea.
