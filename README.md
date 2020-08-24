# SparkML_RandomForest_Classification_Consulting_Project

Business Problem
-----------------

Dog food company want to try to predict why some batches of their dog food are spoiled much quicker than intended.

company want to predict which chemical that has the strongest 
effect out of the amounts of the five preservative chemicals labeled (A,B,C,D) they are using.

The food scientists belive one of the A,B,C or D need help to figure out which one is the problem

In this problem client asks to solve a project that wouldn't require full ML model

Solution:
----------

Used a tree method classifier "FeatureImportances" attribute to find out which parameter had the most predictive power, thus finding out which chemical causes the early spoiling.It wont be typical train/test split workflow.

create a model, fit it on all the data then check which preservative was causing the spoilage.

Check the most important feature out of the Sparse Vector results and that will be the causation for early spoilage.
