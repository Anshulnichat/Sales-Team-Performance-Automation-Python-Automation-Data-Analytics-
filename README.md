# Sales Team Performance (Python Automation) - Data Analytics

1. Introduction

In this project, I worked with an employee dataset containing 10,000 records. Each record included details such as age, gender, department, job title, years of experience, education level, location, and salary.

The main goal was to understand the factors affecting employee salaries and to build a machine learning model that could predict salary based on these factors.

2. Data Understanding

The dataset had 10 columns and no missing values.

Salary values ranged between $25,000 and $215,000.

Key features: Age, Gender, Department, Job Title, Experience Years, Education Level, Location.

3. Exploratory Data Analysis (EDA)

To understand the data better, I created several charts:

Distributions: Looked at how employees were spread across age groups, genders, departments, education levels, and locations.

Scatterplots: Showed relationships like age vs. experience, and experience vs. salary.

Boxplots: Compared salary differences across gender, departments, and education levels.

Heatmap: Showed correlations between numeric features (for example, age and experience are strongly linked).

👉 From these, I noticed:

Experience and job title have a big impact on salary.

Departments also show clear differences in salary levels.

Education level matters, but not as much as experience and department.

4. Model Building

I removed unnecessary columns (Employee_ID and Name).

Converted categorical columns (like gender, department, location) into numeric values using dummy encoding.

Split the dataset into training (80%) and testing (20%) sets.

Trained a Linear Regression model to predict salary.

5. Model Results

Mean Squared Error (MSE): ~17,37,521 → average squared difference between predicted and actual salary.

R² Score: ~0.99 → the model explains about 99% of the salary variation.

⚠️ This R² score is very high, which could mean:

The dataset has very strong linear relationships (salary is almost directly tied to job and experience).

Or, the model might be slightly overfitted.

6. Conclusion

The model predicts salaries very accurately for this dataset.

The most important factors for salary are experience, department, and job title.

Education and location also matter, but to a lesser extent.

Future improvements:

Use Ridge/Lasso regression to reduce overfitting.

Apply cross-validation for stronger evaluation.

Explore other models (like Random Forests) for comparison.

👉 In short, this project shows how data analysis and machine learning can be used to understand salary patterns and build predictive models.
