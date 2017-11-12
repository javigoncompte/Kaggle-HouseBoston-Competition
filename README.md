# Kaggle House Boston Competition 

Kaggle House Boston competition predict prices of houses in the Boston real estate market. Basic Data exploratory done.
Correlation heatmap done on features to understand how each feature behaves with each other.

## Features use to do predictions

Made Dummies so machine learning model could interpret each feature such as description of it having a basement full bath etc. 
Added 1st floor with second floor to make Total area, and extra area was essentially made by adding extra features of the house.
Features that were used were Overall Qualification, Garage living area, total rooms, Lot area, total basement sqf. garage cars, overall conditions,
total square feet, year built, year remodelation, extra square feet.
Polynomial Features with a degree of 3 and not including bias, Standard Scaler to transform non relative units such as quantity vs square feet normalizing.


### Model Used

Elastic net Regression model. With Gridsearcch to find best params which were alpha : 5.0 and l1_ratio of 0.9 gave a score of r2 .8585

```

```



