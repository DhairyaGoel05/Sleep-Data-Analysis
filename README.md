# Data Analysis Project: Sleep and Activity Patterns

## Overview
This project analyzes data related to sleep and activity patterns of individuals. The dataset includes a range of variables that provide insights into the relationship between age, gender, sleep quality, physical activity, dietary habits, and other factors.

## Dataset Description
The dataset contains the following columns:

1. **User ID**: Unique identifier for each individual.
2. **Age**: Age of the individual (in years).
3. **Gender**: Gender of the individual (`m` for male, `f` for female).
4. **Sleep Quality**: A numerical rating (1 to 10) indicating the quality of sleep.
5. **Bedtime**: Time when the individual goes to bed.
6. **Wake-up Time**: Time when the individual wakes up.
7. **Daily Steps**: Number of steps taken daily by the individual.
8. **Calories Burned**: Number of calories burned daily.
9. **Physical Activity Level**: Categorical variable indicating the level of physical activity (`low`, `medium`, `high`).
10. **Dietary Habits**: Categorical variable indicating the dietary habits (`healthy`, `medium`, `unhealthy`).
11. **Sleep Disorders**: Binary indicator for the presence of sleep disorders (`yes`, `no`).
12. **Medication Usage**: Binary indicator for the usage of medication (`yes`, `no`).

## Objectives
The primary goals of this analysis are:
- To identify patterns and trends in sleep quality across different demographic groups.
- To analyze the relationship between physical activity levels and dietary habits with sleep quality.
- To assess the impact of age, gender, and lifestyle factors on overall health metrics.

## Data Processing Steps
1. **Data Cleaning**:
   - Handled missing values and duplicates.
   - Dropped irrelevant columns such as `User ID`.

2. **Feature Engineering**:
   - Calculated `Sleep Duration Hours` using `Bedtime` and `Wake-up Time`.
   - Mapped categorical variables (`Physical Activity Level`, `Dietary Habits`) to numerical codes.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between various factors (e.g., age, gender, activity level) and sleep quality.
   - Examined correlations between numerical variables.

4. **Hypothesis Testing**:
   - Conducted t-tests to compare sleep quality and physical activity across genders, presence of sleep disorders, and medication usage.

5. **Modeling**:
   - Built linear regression models to predict sleep quality based on factors such as age, sleep duration, and calories burned.

## Tools and Techniques
The following tools and techniques were used:
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy.
- **Data Visualizations**: Scatter plots, bar plots, and heatmaps.
- **Statistical Tests**: T-tests for comparing group means.
- **Machine Learning**: Linear regression models to predict sleep quality.

## Key Insights
- **Age vs Sleep Quality**:
  - Identified trends in how sleep quality varies with age.
  - Built a regression model with predictive capabilities.

- **Physical Activity and Sleep Quality**:
  - Higher physical activity levels are associated with better sleep quality.
  - Gender differences were observed in physical activity levels.

- **Dietary Habits**:
  - Individuals with healthier dietary habits tend to have better sleep quality.

- **Sleep Disorders and Medication Usage**:
  - Sleep disorders negatively impact sleep quality.
  - Medication usage shows significant differences in sleep quality.

## Deliverables
- A detailed analysis script performing EDA, hypothesis testing, and modeling.
- Visualizations showcasing key relationships and trends in the data.
- Insights and recommendations for improving sleep and activity patterns.

## Usage Instructions
1. Clone the repository.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python analysis.py
   ```

## Contact
For questions or feedback, please contact Dhairya Goel.


