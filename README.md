# Starbucks-capstone

Medium Post link - https://medium.com/@rnagara1/starbucks-capstone-3c53b71c71d6

# Summary of the Notebook:

The ***Main Goal of this project is to figure out if the customer will respond to the offer given to them***

This Notebook will guide through the process of buidling a Machine Learning Model to achive this using the below steps:

1. Analyse the dataset by exploring them and visualizing.
2. Data Analysis using graphs.
3. Preprocessing the data.
4. Applying ML models for prediction.
5. Analysing the models and understanding the results.

# Questions that this notebook answers are :

1. Percentage of Customers spread across the gender.
2. Salary range of the customers.
3. Distribution of Male and female income of the customer base.
4. Which offer is more popular among which gender.
5. Amount of time taken for each gender to complete the offer given in days.
6. Which offer type is more popular among the gender and age.
7. Which gender like which kind of the offer most?
8. *** Finally predicting will the customer respond to the offer given to them ***

Packages needed:

1. Pandas as pd.
2. Numpy as np.
3. Seaborn as sn.
4. datetime.
5. Sckit learn module.
6. Warnings.

Conclustion:

***This project started with an idea to analyse if the customer just views the offer or completes the given offer.***

The project notebook started with analysing each every dataset individually, visualizing and finding the realtion between various factors like gender, age, income towards the offer. Processing of the dataset took quiet a significant amount of time and effor. The steps included creating features for further analysis and converting the text items into dummy columns. The dimensions like age, income were mapped into groups for categorizing the offers or prediction.

Age was categorized into 4 groups:

 - 1 : teenager
 - 2 : young-adult
 - 3 : adult
 - 4 : elderly

income into 4 groups

 - 1 : Basic
 - 2 : Average
 - 3 : High
 
The quick analysis on the datasets and the graphs:

1. income ranges from 30,000 and 115,000 with most of the customers.
2. it is observed that Male customer base belong to basic salary range 30k to 40k salary range. The high salaried males are less in number.
3. In Female customer base its the average salary holders are leading the higher and lower salaries female base. It indicates Female with average salary more often visit the starbucks.
4. Overall Male with basic salary (40 to 50k) visit most often, then comes the male with average salary and followed by the women with average and high salary category. Overall male population lead the number of visit.
5.  male lead in both viewing the offer and completing the offer more than Female gender. Male gender completes as offer twice the number of female.
6. Observing how long does each gender customer base take on average to complete the offer, small experiment showed that Male and female customers both complete in almost same number of days that is about ***16 days***.
7. young adults  complete the offer quicker and then comes the teenagers who rush to complete the offer.
8.  poplarity level of each offer type among the age groups, The overall Bogo offer is most popular among all the age groups. Next comes the discount both the teenagers and young adult like simlar offers.
9. The accuracies on the test set from decesion tree model was 100% and svm was around 98%. Since our model was binary in nature if they view the offer or complete it based on features like age, gender, income range etc. Finally I would like to finalize Decesion tree model for this offer prediction. 

### Take away from the project:

1. Data Processing skills.
2. Visualizing the dataset using graphs and pandas module.
3. Applying ML models for further prediction.
4. Storytelling from the project.

### Further Improvement:

Application of ML models to predict the which offer type Bogo, discount etc which is best for each indivdual using tensorflow deep learning model. Create a web application usign HTML and CSS.
