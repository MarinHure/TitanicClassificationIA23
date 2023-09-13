# TitanicClassificationIA23
This is a repository for our classification solution for the titanic problem from Kaggle. The repository contains every file needed for execute our solution in Google Colab.

Barredez Rios, Carlos Andres - A01653183
Delgado Rios, Leonardo - A00827915
Joseph Hure, Marin - A01762723
Sánchez Pérez, Raúl Andrés - A01367635

Challenges Faced:

Missing Values: We encountered missing values in the Age, Cabin, and Embarked columns.
Outliers: During our exploration, we detected several outliers in columns such as Age, SibSp, Parch, and Fare.
Data Categorization: Some columns, like Sex and Embarked, were categorical and needed to be transformed to be utilized in predictive models.

Implemented Solutions:

Handling Missing Values: We imputed missing values in Age using median value. For Cabin, given the high amount of missing values, we considered either dropping it or extracting relevant information from it. For Embarked, we replaced missing values with the most common port.
Outlier Management: We employed statistical methods to identify and handle outliers, ensuring they did not skew our model.
Categorical Data Transformation: We transformed categorical columns into numeric values using encoding techniques, like one-hot encoding, so they could be utilized in our models.
