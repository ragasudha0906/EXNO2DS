# EXNO2DS
# AIM:
 To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT

### Import required packages
<img width="1027" height="96" alt="d1" src="https://github.com/user-attachments/assets/e0451e82-d0ae-4d9d-9c9d-b12d6839bc8a" />
### Load dataset

<img width="1180" height="473" alt="d2(1)" src="https://github.com/user-attachments/assets/56941c5d-90c6-4290-9d73-6b0b76b17e7d" />
### Replace missing values

<img width="662" height="75" alt="d3" src="https://github.com/user-attachments/assets/33ae6e80-3fa3-4467-a905-fb8141995d06" />

### Boxplot for outliers

<img width="1209" height="503" alt="d4" src="https://github.com/user-attachments/assets/85c15e09-1eaf-497f-93bb-63447fca4170" />

<img width="1031" height="505" alt="d5" src="https://github.com/user-attachments/assets/d999d463-fcb2-4c33-9514-3066f3457763" />

### Remove outliers using IQR

<img width="919" height="145" alt="d6" src="https://github.com/user-attachments/assets/2aadf07f-9fd4-4627-a74b-3a3bdc979df8" />

### Filtering dataset

<img width="818" height="41" alt="d7" src="https://github.com/user-attachments/assets/db929a78-9b96-43d8-a63e-5cad57db3164" />

### Countplot for categorical data

<img width="1167" height="502" alt="d8" src="https://github.com/user-attachments/assets/bd0aaaec-a965-43c3-83dd-9d0bd8e6b711" />

### Displot for univariate distribution

<img width="1135" height="599" alt="d9" src="https://github.com/user-attachments/assets/1862dc23-57bc-4f00-ad1c-a1005824d520" />

### Cross-tabulation

<img width="940" height="206" alt="d10" src="https://github.com/user-attachments/assets/51f23a58-17a3-4b7f-a09b-2a24394ab33c" />

### Heatmap of correlation
<img width="1291" height="716" alt="d11" src="https://github.com/user-attachments/assets/48d2a3df-a264-4a25-8978-d0f061cdb513" />


# RESULT
In this experiment, the Titanic dataset was cleaned and explored using EDA techniques. Missing values in the Age column were filled with the median, while Embarked was filled with the mode, and the Cabin column was dropped due to excessive null values. Boxplots were used to detect outliers in Age and Fare, showing significant outliers in Fare. These Fare outliers were removed using the Interquartile Range (IQR) method to make the data more balanced. A countplot of Sex revealed that there were more male passengers than females on board. The distribution of Age showed most passengers were between 20 and 40 years old. Cross-tabulation between Pclass and Survived indicated that first-class passengers had higher survival rates, while third-class had the lowest. The heatmap of correlations among numeric features showed that Fare and Pclass were strongly related, and survival was moderately linked to both Fare and Pclass. Family-related features like SibSp and Parch showed weak correlations. Overall, the EDA highlighted clear socio-economic and demographic patterns in survival outcomes.
