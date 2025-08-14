## PREDICTING MENTAL HEALTH SCORES BASED ON WELLNESS APP USAGE AND LIFESTYLE FACTORS: A CROSS-SECTIONAL ANALYSIS


## Objective
The objective of this project is to investigate the relationship between screen time and mental health outcomes. The study examines how various forms of screen usage (phone, laptop, tablet, TV, social media) relate to mental health scores, depression, anxiety, sleep quality, and lifestyle factors.

-----

## Source
Dataset: Impact of Screen Time on Mental Health Dataset – https://www.kaggle.com/datasets/khushikyad001/impact-of-screen-time-on-mental-health. It is an observational, cross-sectional data containing demographic, behavioral, lifestyle, and psychological health metrics.

------

## Target Variable
Mental Health Score – continuous variable representing the overall mental health status of participants.

-----

## Methodology

## Data Preprocessing
- Combined multiple screen time columns into a Total_screen_time variable.
- Removed redundant columns after aggregation.
- Handled missing values and ensured consistent data types.

## Exploratory Data Analysis (EDA)
- Histograms, scatter plots, line plots, and boxplots to identify trends and patterns.
- Pearson correlation heatmap to examine relationships among variables.

## Modeling
- Implemented Linear Regression, Random Forest Regressor, and Support Vector Regression (SVR).
- Evaluated models using MAE, MSE, RMSE, and R² score.

-----

## Observations
- Mental health scores showed a roughly uniform distribution across participants.
- Scatter plot analysis revealed weak or no linear correlation between depression scores and screen time.
- Wellness app users showed slightly higher mental health scores at certain sleep quality levels compared to non-users.
- Gender differences in mental health scores were minimal.
- Correlation analysis revealed very weak relationships between total screen time and mental health variables.

-----

## Key Insights
- No strong direct correlation between total screen time and mental health score was found.
- Wellness app usage may have a marginal positive influence on mental health, especially when combined with good sleep quality.
- Depression and anxiety scores do not show a consistent trend with screen time.
- Lifestyle factors like sleep quality and physical activity may play a bigger role than screen time alone.

------

## Conclusion
While screen time is often perceived as a major factor influencing mental health, this analysis suggests that the relationship is weak in this dataset. Other lifestyle factors, such as sleep quality, physical activity, and wellness app usage, may have more substantial impacts on mental health outcomes. Future research could explore longitudinal data and interaction effects between lifestyle factors for deeper insights.
