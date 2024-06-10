
<<<<<<< HEAD

![alt text](Obesity.jpeg)
=======
# Predicting Obesity Levels Based on Lifestyle Factors
This project aims to predict obesity levels among individuals based on various lifestyle and physical factors. By analyzing the relationship between these factors and obesity levels, we aim to provide insights that can help in the prevention and management of obesity. The dataset used in this project includes attributes related to eating habits, physical activity, and other lifestyle factors.
>>>>>>> 62207a245c8c8c142a31e4ae804ba720331dbb5c

![Chilhood_Obesity](/Images/Childhood-Obesity-Problem.jpg)
[IMG Referenece](https://beaumonteh.com/childhood-obesity-problem/)
## Objectives:

<<<<<<< HEAD


### Locate the data, clean the data, and build the dataframe
=======
1. To develop predictive models that accurately classify individuals into different obesity levels based on their lifestyle and physical characteristics. 
2. We aim to investigate the correlation between various factors (variables) and the target variable (obesity) to understand their relationships and impacts.
3. Our goal is to develop a predictive model through machine learning that can accurately estimate the likelihood of obesity based on these factors. 
4. By evaluating and refining our model, we strive to enhance its accuracy in predicting obesity levels from input variables, ultimately aiming for a robust and reliable predictive tool.
>>>>>>> 62207a245c8c8c142a31e4ae804ba720331dbb5c


## Data Description:

The dataset includes the following features:

* Gender: Categorical variable indicating the gender of the individual.
* Age: Continuous variable representing the age of the individual.
* Height: Continuous variable representing the height of the individual.
* Weight: Continuous variable representing the weight of the individual.
* Family History with Overweight: Binary variable indicating whether there is a family history of being overweight.
* High Caloric Food Consumption (FAVC): Binary variable indicating whether the individual frequently consumes high-caloric food.
* Vegetable Consumption (FCVC): Continuous variable indicating the frequency of vegetable consumption in meals.
* Number of Main Meals (NCP): Continuous variable representing the number of main meals per day.
* Consumption of Food Between Meals (CAEC): Categorical variable indicating the frequency of food consumption between meals.
* Smoking Habits (SMOKE): Binary variable indicating whether the individual smokes.
* Daily Water Intake (CH2O): Continuous variable representing the daily water intake.
* Monitoring of Calorie Intake (SCC): Binary variable indicating whether the individual monitors their calorie intake.
* Frequency of Physical Activity (FAF): Continuous variable representing the frequency of physical activity per week.
* Screentime on Technological Devices (TUE): Continuous variable indicating the time spent using technological devices per day.
* Alcohol Consumption (CALC): Categorical variable indicating the frequency of alcohol consumption.
* Mode of Transportation (MTRANS): Categorical variable representing the mode of transportation usually used by the individual.
* Obesity Level (Target): Categorical variable indicating the obesity level of the individual (e.g., Normal Weight, Overweight, Obesity Type I, etc.)

## Data Sources: 
* Data sourced from UC Irvine Machine Learning Repository using ‘unimlrepo’ 
* Estimation of Obesity Levels Based On Eating Habits and Physical Condition . (2019). UCI Machine Learning Repository. 
[Obesity Levels](https://doi.org/10.24432/C5H31Z)

## Modeling Techniques:
1. Neural Networks: 
* 


2. Logistic Regression:
 * 

3. Support Vector Machine (SVM):

*  SVM was used to classify individuals into different obesity levels based on their lifestyle and physical factors. This machine learning technique helps in identifying the obesity category of an individual (e.g., Normal Weight, Overweight Level I, Obesity Type I, etc.) by analyzing various input features

## Locate the data, clean the data, and build the dataframe

* Collect Data from various sources;
* Dataset features a combination of real-world and artificially 
generated data.
* Data analysed and matched against expected categorical 
values. Any features with entries which were outside the 
expected categorical or integer measure need to be explored.
* Binary data is converted to numerical form, making it suitable 
for machine learning models.
* Categorical data is replaced with the appropriate categorical 
measure for consistency in analysis.
* Discrete categorical data (i.e 1, 2 or 3) is replaced with the 
appropriate categorical measurement to represent data 
accurately.

### Data Normalization:
* Ensures all data is in a suitable format for model training.
Conclusion.
* Data Preparation: The code prepares the obesity dataset for analysis
by converting categorical data to numerical data, creating new 
features, and normalizing the data.

### Feature Engineering:
* A new BMI feature is created, representing the ratio of weight 
to height squared.
* A new BMI feature is created, and other features are bucketed into categories.
* Features are bucketed into categories to simplify analysis and 
improve model performance.
* Readiness for Modeling: The processed data is now suitable for training machine learning models to predict obesity levels based on various factors.

### Explore the correlation, building a regression analysis and plot


### Train the machine to build a model 
* Train machine learning models using the processed data.
* Evaluate model performance and interpret results.
* Explore feature importance to understand which factors 
contribute most to obesity levels.
* By following these steps, you can build predictive models and gain 
insights into the factors affecting obesity

### Evaluate the model and choose the best one

### Input variables and predict
