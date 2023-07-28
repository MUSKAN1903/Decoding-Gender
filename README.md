# Decoding-Gender
A Facial Feature-Based Classification 
Explore Gender Classification through Facial Features & Discover how facial dimensions can provide valuable insights into distinguishing gender with our machine learning project.

In this project, i have chosen to deal with the gender classification of human beings based on their facial features and structures such as nose, lips, forehead dimensions and other features.

# CONTENT 
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/de66fe70-1253-4bc7-aeb3-5e73a62c821e)
The Dataset was taken from Kaggle and contains 7 features and a label column.
- **Long_hair** - This column contains O's and 1's where 1 is "long hair" and 0 is "not long hair".
- **Forehead_width_cm** - This column is in CM's. This is the width of the forehead.
- **Forehead_height_cm** - This is the height of the forehead and it's in Cm's.
- **Nose_wide** - This column contains O's and 1's where 1 is "wide nose" and O is "not wide nose".
- **Nose_long** - This column contains O's and 1's where 1 is "Long nose" and 0 is "not long nose".
- **Lips_thin** - This column contains O's and 1's where 1 represents the "thin lips" while O is "Not thin lips".
- **Distance_nose_to_lip_long** - This column contains O's and 1's where 1 represents the "long distance between nose and lips" while 0 is "short distance between nose and lips".
- **Gender** - This is either "Male" or "Female".

## STEPS PERFORMED
- Importing Required Libraries
- Data Collection
- Data Cleaning
- EXPLORATORY DATA ANALYSIS ( EDA )
- Data Preparation
- Model Training
- Model Evaluation
- Results

Analysing the data
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/4277e709-94ce-4230-88da-0f17b6cc580b)

LIPS DIMENSION BY GENDER
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/c059af72-5953-4d50-aa45-163b6f75a984)
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/d7f0085f-b7a2-4839-b2f8-e10bd035af6f)

We can see that most of the females have wider lips and shorter distance between the nose and lips than the males.

FOREHEAD DIMENSION BY GENDER
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/5d765cd5-ca93-4792-a063-86a16481574c)

we can see that males have more wide and high forehead than females.

HAIR DIMENSION BY GENDER
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/6c14982b-dfee-4fbb-bc5d-56bf77f8da8d)

For this dataset , We can see that there is very small diferences in hair length between males and females.

NOSE DIMENSION BY GENDER
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/ff9e37ef-18fb-4ae3-8c7f-01ee75e3d8f5)

We can see that females have thinner and shorter noses than males.

Correlation between the features
![image](https://github.com/MUSKAN1903/Decoding-Gender/assets/70433658/d3578899-6dca-4503-887f-a45488918c88)

### CONCLUSION
- In this project I worked on a dataset of facial features and tried to predict gender according to those characteristics.
- After analysing the data it could be seen that there is a correlation between the forehead,nose,lips and the gender type.
- No correlation was found between hair length and gender.
- In the model training it can be seen that the percentage of accuracy in all of them is relatively high - over 95% for all models.
- Out of them the model KNN showed the highest percentage of accuracy approx 97%.













