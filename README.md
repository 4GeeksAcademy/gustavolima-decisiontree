# Decisition Tree Model Project (and Random Forest)

This project is all about a Categorical problem to be solved, where a person would be Diabetic or not, using free to use dataset about Diabetes data from the US. 
For this one the goal is to use a Decision Tree Model and at the same time trying to optimize it. 

## 📔 Key Takes

Despite the data being of inferior quality, an Exploratory Data Analysis was conducted and all data cleaning and feature engineering was done in order to train the model. We can see the quality and possibilities of a model accuracy by the parallel coordinates plot of the data: 

<img src="https://github.com/4GeeksAcademy/gustavolima-decisiontree/blob/main/assets/parallelcoord.png" width="500">

I also tried using different features combinations in order to see if I could get better results, but unfortunately not. 

The only way to optimize the algorithm was to switch from a Decision Tree model to a Random Forest model and boosting it's hyperparameters. a 20% accuracy boost was possible using this method. For future reference, perhaps using XGBoost could improve a bit more our accuracy, but the key point is the quality of the data presented to work with. 
