# Sleep and Lifestyle Analysis

## 1. Project Overview

This project analyzes the relationship between lifestyle factors and sleep disorders using a dataset containing information on individuals' sleep, health, and daily lifestyle characteristics. The analysis focuses on identifying patterns in sleep disorders across factors such as age, gender, occupation, stress level, sleep quality, sleep duration, physical activity, and BMI category. The project was developed in Power BI to explore patterns and communicate key findings through interactive visualizations.

## 2. Data Preparation

The dataset was cleaned and prepared in Power Query before analysis. This included standardizing inconsistent category names, such as changing "Normal Weight" to "Normal" and "Software Engineer" to "Engineer", and checking data types and values for consistency.

## 3. Key Findings

### Overall Sleep Disorder Prevalence

Out of 374 individuals in the dataset, 155 had a recorded sleep disorder, giving an overall observed prevalence of approximately **41.44%**. The sleep disorders recorded in the dataset were Insomnia and Sleep Apnea.

Throughout this analysis, **observed prevalence** refers to the percentage of people with a sleep disorder within a specific group. For example, an age-group prevalence is calculated as the number of people with a sleep disorder in that age group divided by the total number of people in that age group. Therefore, the percentages represent prevalence within each group rather than the proportion of the entire dataset.

### Age and Sleep Disorder Prevalence

The **45–49 age group** had the highest observed sleep-disorder prevalence at approximately **86%**, followed by the **50+ group at 60.42%**. This suggests that sleep disorders were more prevalent among the older age groups in this dataset.

### Age and Type of Sleep Disorder

The prevalence of specific sleep disorders varied across age groups. **Insomnia was most prevalent among individuals aged 40–44 at 52.81%**, followed by the 45–49 group at 46.43%. **Sleep Apnea was most prevalent among the 50+ group at 52.08%**, followed by the 45–49 group at 39.29%. This shows that the distribution of sleep-disorder types differed across age groups.

### Gender and Sleep Disorder Prevalence

Females had a higher observed sleep-disorder prevalence than males. **55.68% of females** had a recorded sleep disorder compared with **27.51% of males**. This shows a notable difference in observed prevalence between the two gender groups within the dataset.

### Occupation and Sleep Disorder Prevalence

Sleep-disorder prevalence varied considerably across occupations. **Sales Representatives had the highest observed prevalence at 100% (2 of 2 individuals)**, followed by Salespeople at **93.75%** and Nurses at **87.67%**. The Sales Representative result should be interpreted cautiously because the group contained only two individuals. These findings show differences across occupations but do not establish that occupation causes sleep disorders.

### Stress Level and Sleep Disorder Prevalence

**Stress Level 7** had the highest observed sleep-disorder prevalence at **94% (47 of 50 individuals)**, mainly associated with Insomnia, which had a prevalence of **82%**. Stress Level 8 had a prevalence of **52.86%**, with Sleep Apnea accounting for **48.57%**, while Stress Level 3 had a prevalence of **43.66%**. The results did not show a simple linear relationship between stress level and sleep disorders.

### Sleep Quality and Sleep Disorder Prevalence

Sleep-disorder prevalence varied considerably across sleep-quality levels. Quality **4 and 5 recorded 100% prevalence**, although these groups contained only **5 and 7 individuals** respectively. Among the larger groups, prevalence was highest at Quality **6 (61.90%)** and lowest at Quality **8 (7.34%)**, before increasing to **46.48% at Quality 9**.

### Physical Activity and Sleep Disorder Prevalence

Physical activity was grouped into **Low (30–49), Moderate (50–69), and High (70–90)** based on the dataset's observed range. The **Low activity group had the highest observed sleep-disorder prevalence at 52.98%**, followed by the **High activity group at 47.52%**, while the **Moderate activity group had the lowest prevalence at 9.76%**. The results show differences in observed sleep-disorder prevalence across the activity bands, but they do not establish that physical activity directly causes or prevents sleep disorders.

Overall, the analysis identified differences in observed sleep-disorder prevalence across demographic and lifestyle factors. These findings describe patterns within the dataset and should not be interpreted as evidence that any of the factors directly cause sleep disorders.

## 4. Tools Used

- **Power BI** — Data visualization and analysis
- **Power Query** — Data cleaning and transformation
- **Excel** — Initial data inspection and preparation

## 5. Limitations

The dataset contains some repetitive characteristics across records, which may affect how representative the observed patterns are. The analysis describes associations within this dataset and does not establish causal relationships between lifestyle factors and sleep disorders.
