# Exploratory Data Analysis and Machine Learning
Exploratory Data Analysis and some Linear Regression machine learning on a public data set done by me, Khoo Ed Win. This project was done with the intention of familiarising myself with data analysis, python and machine learning.
This notebook is used for practice and learning purposes. The dataset used in this notebook is publically available via Kaggle at the following
URL: [https://www.kaggle.com/datasets/rafsunahmad/best-country-to-live-in-2024/code] by Rafsun Ahmad.

## Results
| Model               | MSE       | Cross-Validation Score | R-squared Score |
| ------------------- |:---------:| ----------------------:|----------------:|
| Linear Regression   | 0.003023  | 0.996526               | 0.996932        |
| Support Vector      | 1.187656  | -0.204841              | -0.205358       |
| Random Forest       | 0.101470  | 0.916920               | 0.897017        |
| K-Nearest Neighbour | 1.725262  | -0.401874              | -0.750977       |

## Evaluation
1. **Linear Regression**
--*THad the lowest Mean Squared Error (MSE), the highest cross-validation score, and the highest R-squared score. This indicates that it has the best performance among the four models. It's making the most accurate predictions with the least error, and it's explaining a high proportion of the variance in the target variable.

2. **Support Vector**
--*Had a high MSE, a negative cross-validation score, and a negative R-squared score. This indicates that it's performing poorly. It's making inaccurate predictions with a high error, and it's not explaining the variance in the target variable well.

3. **Random Forest**
--*Had a relatively low MSE, a high cross-validation score, and a high R-squared score. This indicates that it's performing well, but not as well as the Linear Regression model. It's making fairly accurate predictions with a relatively low error, and it's explaining a good proportion of the variance in the target variable.

4. **K-Nearest Neighbour**
--*Had the highest MSE, a negative cross-validation score, and a negative R-squared score. This indicates that it's performing the worst among the four models. It's making the least accurate predictions with the highest error, and it's not explaining the variance in the target variable well.
