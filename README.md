# Laptop Price Prediction

# Exploratory Data Analysis
Exploratory Data Analysis refers to the critical process of performing initial investigations on
data so as to discover patterns,to spot anomalies,to test hypotheses and to check assumptions
with the help of summary statistics and graphical representations.
Dataset selected Laptop Price Prediction dataset.
1)Details about dataset-
● Laptop price is one of the largest dataset containing details of different laptops. The
dataset contains details related to laptops. The dataset have 1300 laptop models with
contents :-
I. Company Name
II. Product Name
III. Laptop Type
IV. Screen Inches
V. Screen Resolution
VI. CPU Model
VII. RAM Characteristics
VIII. Memory
IX. GPU Characteristics
X. Operating System
XI. Laptop's Weight
XII. Laptop's Price
● No of rows = 1303
● No of columns = 13
● Data has only float and integer values, string.
● No variable column has null/missing values.
● Dataset is from Kaggle containing information of various laptops manufactured by
different companies like Dell,Lenovo,Apple and their different variants.The laptops differ
from each other by their Ram as different laptops have different GB of RAM,their
processor some Intel I3,I5 processor similarly many other features.A image of few rows
of dataset is shown below
![image](https://github.com/Eshani-R-Sawant/Laptop-Price-Prediction/assets/78209696/e6781f42-8b4b-40ce-8f87-49099be909d7)

1. Conditions [Decision Nodes]
2. Result [End Nodes]
The branches/edges represent the truth/falsity of the statement and make a decision
based on the branches/edges.
● Decision Tree Regression:
Decision tree regression observes features of an object and trains a model in the
structure of a tree to predict data in the future to produce meaningful continuous
output. Continuous output means that the output/result is not discrete, i.e., it is
not represented just by a discrete, known set of numbers or values.
4)Data preprocessing and technique implementation
● Data Preprocessing
First we checked for null values in our dataset. There are no values in our dataset.Then
we performed feature engineering as our data is noisy data. It contains a lot of
information so we extracted meaningful information from the data like getting numeric
value for Ram and weight from string value.
Replacing inches ,x,y screen resolution into PPI index.Converting processor,operating
system ,GPU into categorical value.
Visualization Of histogram of price which is left skewed as more laptop at lower price are
sold and produced.

![image](https://github.com/Eshani-R-Sawant/Laptop-Price-Prediction/assets/78209696/a6c58532-2d06-4307-8191-7a235ffd53b4)

.
● Technique implementation
We splitted the dataset into train and test dataset and applied our decision tree
regression model on our dataset.
5)Result
![image](https://github.com/Eshani-R-Sawant/Laptop-Price-Prediction/assets/78209696/b57bf75a-55d0-451e-bd2b-cfefe9f51d46)

● We have plotted a scatter plot to visualize the prediction and this gives us a great result.
● R2 score= 0.9969123656945321
● MAE =0.0014372803572055256
● I also tried to predict the value for a row in the test dataset and got the exact same price
for the given specifications provided in the test dataset.
6)Conclusion
After testing on previous works done on the dataset I applied decision tree regression on
my dataset which fit my data perfectly giving best results and accurate predictions.I have
learned and analyzed my dataset and chosen this technique that works best on my
model of laptop price prediction. My model is very helpful in predicting laptop price
prediction based on features of the laptop chosen.
