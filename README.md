# Campus_placement

# Machine Learning Project README

## Introduction

Welcome to the Machine Learning project for predicting placement status using the "Placement_Data_Full_Class" dataset. In this project, we explore, preprocess, and build predictive models to determine whether a student will be placed or not after their educational program. The project's primary goal is to analyze the factors that influence placement status and evaluate the performance of various machine learning models in predicting it.

## Exploratory Data Analysis (EDA)

### Initial Data Exploration

We began by importing necessary libraries, loading the dataset, and conducting initial data exploration:

- Imported Pandas for data manipulation, Matplotlib for data visualization, and essential machine learning libraries.
- Loaded the dataset from "/content/Placement_Data_Full_Class.csv" and displayed its initial information.
- Checked for missing values in the dataset and removed columns that were not relevant for our prediction task.

### Numerical Feature Analysis

We conducted a thorough analysis of numerical features concerning placement status using Kernel Density Estimation (KDE) plots. This allowed us to visualize the distribution of key numerical features in relation to placement status:

- `ssc_p` (Secondary Education Percentage)
- `hsc_p` (Higher Secondary Education Percentage)
- `degree_p` (Undergraduate Degree Percentage)
- `etest_p` (E-test Percentage)
- `mba_p` (MBA Percentage)

![image](https://github.com/AkshayRamakrishnann/Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach/assets/111365771/6bfe07a2-d23f-496a-a2c0-f4559935ffc4)

### Gender vs. Placement

We investigated the relationship between gender and placement status using a stacked bar chart. This helped us understand how gender impacts placement:

- The chart provides insights into the number of placed and not-placed students by gender.
- We calculated placement rates for each gender category and discussed the observed gender imbalance.

![image](https://github.com/AkshayRamakrishnann/Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach/assets/111365771/1becef25-4605-410e-a147-3a3dd54100d4)


## Preprocessing

### Data Encoding

To prepare the data for modeling, we performed data encoding:

- Encoded the target variable 'status' using Label Encoding, converting it into numerical values.
- Performed one-hot encoding for categorical features such as 'gender', 'ssc_b', 'hsc_b', 'hsc_s', 'degree_t', 'workex', and 'specialisation.'

## Models Used

To predict placement status, we employed several machine learning classifiers, including:

- **Decision Tree**: Achieved an accuracy of 0.84.
- **Random Forest**: Achieved an accuracy of 0.77.
- **K-Nearest Neighbors**: Achieved an accuracy of 0.79.
- **Naive Bayes**: Achieved an accuracy of 0.74.

We visualized and compared the accuracy of these models using a bar plot.


![image](https://github.com/AkshayRamakrishnann/Predicting_Hotel_Booking_Cancellations__A_Machine_Learning_Approach/assets/111365771/7b23e143-8137-4fe4-87b7-8bf340fb16aa)

## Conclusion

In conclusion, this project aimed to predict student placement status using various machine learning models. We found that the Decision Tree model performed the best among the models evaluated, achieving an accuracy of 0.84. However, further analysis and feature engineering could improve the models' performance. The gender imbalance among placed and not-placed students was also discussed.

Please explore the code and results in this repository to gain a deeper understanding of the project. If you have any questions or feedback, feel free to reach out.

