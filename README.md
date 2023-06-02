# Ex03-Univariate-Analysis

Date - 

Colab Link - https://colab.research.google.com/drive/1vwpu5ldecbCMvJ_7w1axvbfV5AZsMTUO?usp=sharing

Github Link - https://github.com/KATHIR1611/Ex03-Univariate-Analysis

# AIM

  To read the given dataset and perform univariate analysis.

Explanation

  Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm

Step1
Read the given data.

Step2
Get the information about the data.

Step3
Remove the null values from the data.

Step4
Mention the datatypes from the data.

Step5
Count the values from the data.

Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program


Developed by :Kathirvelan.K

Registration Number : 212221220026

```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
print(df)

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Row ID'].value_counts()

sns.boxplot(x="Row ID", data=df)

sns.countplot(x="Row ID", data=df)

sns.distplot(df["Row ID"])

sns.histplot(x="Row ID", data=df)
```
# Output

Dataset

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%201.png)

Dataset info

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%202.png)

Dataset describe

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%203.png)

Null value

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%204.png)

Data types

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%205.png)

Value count

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%206.png)

Boxplot

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%207.png)

Count plot

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%208.png)

Distribution plot

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%209.png)

Histogram plot

![](https://github.com/KATHIR1611/Ex03-Univariate-Analysis/blob/main/ds%2010.png)

# Result

  Thus we have read the given data and performed the univariate analysis with different types of plots.


