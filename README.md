# Personal Key Indicators for heart disease
## by Huzaifa Shehu Imam


## Personal Key Indicators for heart disease

The dataset was obtained from the CDC and is a major part of the Behavioral Risk Factor Surveillance System (BRFSS), which conducts annual telephone surveys to gather data on the health status of U.S. residents. According to the CDC, heart disease is one of the leading causes of death for people of most races in the US (Negroes, American Indians and Alaska Natives, and Caucasians). About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Other key indicators include diabetic status, obesity (high BMI), sedentary lifestyle or drinking too much alcohol. Detecting and preventing the factors that have the greatest impact on heart disease is very important in healthcare. The original dataset contained 401,958 rows and 279 columns, the cleaned dataset posted on Kaggle however contains only 20 columns/variables of different types, which are of relevance to heart disease.
The dataset could obtained at the following address: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

## Summary of Findings

Based on our analysis of the distribution of the variables in the dataset, we found that heart disease was more prevalent amongst men than women, in addition, we found that it was more prevalent in men within the 80 years and over age group. It was also commoner amongst Caucasians than in other races/ethnicities. Furthermore, I sought to look at the relationship between some of the variables using a correlation heat mat, which revealed no signifficant positive or negative correlation between any of the variables. Only a weak positive correlation was found between physical and mental health. More established relationships, such as that between physical, mental health and sleep time, smoking and stroke etc were all found to not be correlated surprisingly! The dataset aalso omitted vital information about the 2 other key indicators, having all three key indicators could have led to a more robust statistical investigation.

## Key Insights for Presentation

I started off by visualising the distribution of our outcome of interest, i.e Heart disease, accross the research population, then gender and finally, by ethnicity. I then analysed the data further to get an insight into the prevalence of smoking and alcoholism within the study population, which are key risk factors not only for heart disease but also for stroke. I also looked at the prevalence of stroke within the research population. I also considered a better way to present the BMI by classifying the scores into categories, thereby adding a new column to the dataframe.
I used a correlation heatmap inorder to investigate correlation between the numerical variables, I also utilised a pairplot to look into the distribution of the risk factors of heart disease within different BMI categories