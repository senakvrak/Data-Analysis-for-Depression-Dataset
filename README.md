# Data-Analysis-for-Depression-Dataset

## Project Overview

This project explores and analyzes a dataset related to depression and various personal and lifestyle factors. The goal is to uncover insights about depression risk based on factors such as age, income, marital status, smoking habits, physical activity levels, alcohol consumption, and more. The analysis aims to help understand patterns, create new features, and perform statistical tests to guide potential intervention strategies for mental health improvement.

The dataset contains data points related to individuals, including:

* Demographic information (e.g., age, marital status, education level, income)
* Health-related behaviors (e.g., smoking status, alcohol consumption, physical activity)
* Mental health indicators (e.g., history of mental illness, family history of depression)
* Lifestyle and wellness features (e.g., dietary habits, sleep quality)

This project performs data cleaning, feature engineering, exploratory data analysis (EDA), and statistical tests to explore relationships between these factors and depression risk.

## Dataset

The dataset used in this project is publicly available on Kaggle. It includes various features related to people's lifestyles and health history. More details about the columns can be found on the [Kaggle dataset page](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset).

Columns in the Dataset:

* **Age**: The age of the individual in years.
* **Marital Status**: The marital status of the individual.
* **Education Level**: The highest level of education attained.
* **Number of Children**: The number of children the individual has.
* **Smoking Status**: Indicates whether the individual smokes or not.
* **Physical Activity Level**: The level of physical activity undertaken by the individual.
* **Income**: The individual's annual income.
* **Alcohol Consumption**: The individual's level of alcohol consumption.
* **Dietary Habits**: The individual's dietary habits (e.g., healthy, moderate, unhealthy).
* **Sleep Patterns**: The quality of the individual's sleep.
* **History of Mental Illness**: Whether the individual has a history of mental illness.
* **History of Substance Abuse**: Whether the individual has a history of substance abuse.
* **Family History of Depression**: Whether the individual has a family history of depression.
* **Chronic Medical Conditions**: Whether the individual has any chronic medical conditions.

## Tools and Libraries Used

* **Python**: The primary programming language utilized for data analysis and processing.
* **Pandas**: Used extensively for data cleaning, manipulation, and handling missing values.
* **Matplotlib & Seaborn**: Employed for creating visualizations, such as bar plots and heatmaps, to explore relationships in the dataset.
* **NumPy**: Used for efficient numerical operations and calculations.
* **SciPy**: Applied for conducting the Chi-Square test and other statistical analyses.

## Objective

The main objectives of the analysis are:

1. Impute missing data in the dataset.
2. Create new features like the **Depression Risk** score and the **Healthy Lifestyle Score**.
3. Analyze the relationships between lifestyle factors (e.g., smoking, alcohol consumption, physical activity) and depression risk.
4. Conduct statistical tests like the Chi-Square Test to examine associations (e.g., between smoking status and family history of depression).
5. Visualize insights and relationships between various features.

## Key Steps in the Project

1. **Data Preprocessing**: Clean the dataset by handling missing values and outliers, ensuring data consistency.
2. **Feature Engineering**: Create new features such as the Healthy Lifestyle Score, Depression Risk, and Family Status (based on marital status and number of children).
3. **Statistical Testing**: Use tests such as the Chi-Square Test to check the relationship between smoking status and family history of depression.
4. **Visualization**: Create bar plots, stacked bar charts, and other visualizations to interpret the data better and present findings.

## Results

The analysis revealed several noteworthy findings. Individuals categorized as "Married with children" were identified as having the highest depression risk, followed by single individuals, while those who were "Married without children" exhibited the lowest risk. A composite Healthy Lifestyle Score, calculated based on factors such as physical activity level, dietary habits, smoking status, and alcohol consumption, demonstrated that individuals with higher scores were less likely to experience depression. However, the limited variability in the scores, mostly concentrated around 0 and 2, suggests a need for more diverse lifestyle patterns in the dataset. A Chi-Square test uncovered a strong association between smoking status and family history of depression, with a significant p-value of 2.98e-126. This relationship was further supported by visualizations, which highlighted distinct patterns in smoking behavior among individuals with and without a family history of depression. Overall, the results emphasize the influence of lifestyle choices, such as maintaining a healthy diet, avoiding smoking, and consuming alcohol in moderation, in mitigating depression risk. Furthermore, family structure also plays a significant role in shaping mental health outcomes, as evidenced by the higher depression risk observed among individuals with children.

## Kaggle
[Kaggle Website](https://www.kaggle.com/code/senakivrak/data-analysis-with-depression-dataset)
