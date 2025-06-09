## Boston-Hoston-Prediction
# Project Overview

In this project, I developed and evaluated a multiple linear regression model aimed at predicting the market value of homes in the suburbs of Boston, Massachusetts. By leveraging key features from the dataset—such as crime rate, proximity to employment centers, and property tax rates—I built a model capable of estimating housing prices with a focus on accuracy and interpretability. This project not only demonstrates my understanding of supervised learning techniques but also showcases my ability to handle real-world data, apply proper preprocessing, and validate model performance. Predictive models like this one can serve as powerful tools for stakeholders in the real estate industry, from agents to analysts, helping them make informed decisions backed by data.
✅ 1. RM

"Average number of rooms per dwelling"

    It shows how many rooms a house has on average.

    More rooms → usually higher price.

🧠 Why it matters: Bigger houses (more rooms) tend to be more expensive.
✅ 2. LSTAT

"% lower status of the population"

    It shows the percentage of people in the area with low income or education.

    Higher LSTAT → poorer neighborhood.

🧠 Why it matters: Homes in areas with a high LSTAT value often have lower prices.
✅ 3. PTRATIO

"Pupil-teacher ratio by town"

    It tells how many students there are per teacher in schools.

    Higher PTRATIO → crowded schools → can lower house value.

🧠 Why it matters: People prefer towns with better schools (lower PTRATIO), so house prices can go up there.
✅ 4. MEDV

"Median value of owner-occupied homes in $1000s"

    This is your target variable (what you're trying to predict).

    For example, if MEDV = 24, it means $24,000.

🧠 Why it matters: Your model learns patterns in the other columns to predict this value.

